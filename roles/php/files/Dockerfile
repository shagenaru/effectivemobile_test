FROM php:8.2-fpm

RUN docker-php-ext-install pdo pdo_mysql

COPY ./www /var/www

EXPOSE 9000
