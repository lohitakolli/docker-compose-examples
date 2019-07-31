FROM php:5.6-fpm

RUN apt-get update && apt-get install -y \
        

RUN docker-php-ext-install mysql mysqli pdo pdo_mysql

COPY ./uploads.ini /usr/local/etc/php/conf.d/uploads.ini
