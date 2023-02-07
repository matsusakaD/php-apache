# php-apache

[PHP公式 Docker](https://github.com/docker-library/php) を元に、pgsql/pdo/intl/zip を追加したもの。

## 8.0.24

### build 

```
$ cd 8.0.24
$ docker buildx build --platform linux/amd64,linux/arm64/v8 -t kaz29/php-apache:8.0.24 .
$ docker buildx build --platform linux/amd64,linux/arm64/v8 -t kaz29/php-apache:8.0.24 --push .
```
### run 

```
$ docker run -it --rm -d --name php-apache-8.0.24 kaz29/php-apache:8.0.24
```
