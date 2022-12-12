FROM php:7.4.25-fpm-alpine3.13

RUN apk add --update

RUN apk add --no-cache zip libzip-dev

RUN apk add --no-cache gd libpng-dev
  
RUN docker-php-ext-install zip

RUN docker-php-ext-install gd