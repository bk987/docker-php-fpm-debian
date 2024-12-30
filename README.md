# docker-php-fpm-debian

[https://hub.docker.com/r/bk987/php-fpm-debian](https://hub.docker.com/r/bk987/php-fpm-debian)

```shell
cd docker-php-fpm-debian/8.3

docker build -t bk987/php-fpm-debian:8.3 -f Dockerfile .

docker tag bk987/php-fpm-debian:8.3 bk987/php-fpm-debian:latest

docker push bk987/php-fpm-debian:8.3

docker push bk987/php-fpm-debian:latest
```