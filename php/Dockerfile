FROM php:fpm-alpine
#RUN docker-php-ext-install opcache
#COPY php/production/opcache.ini /usr/local/etc/php/conf.d/opcache.ini
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
#RUN apt-get update && apt-get upgrade -y
COPY ./src /var/www/html