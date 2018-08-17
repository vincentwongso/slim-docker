FROM php:7.2-fpm
LABEL maintainer="Vincent Wong"

COPY . /srv/app/
COPY .docker/php/php.ini /usr/local/etc/php/php.ini

WORKDIR /srv/app/

RUN chown -R www-data:www-data /srv/app