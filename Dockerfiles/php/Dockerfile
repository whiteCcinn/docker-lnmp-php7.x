FROM php:7.1.11-fpm

MAINTAINER caiwh <471113744@qq.com>

RUN docker-php-ext-install pdo_mysql

Add composer /usr/local/bin/composer

Add php.ini /usr/local/etc/php/php.ini

RUN chmod 755 /usr/local/bin/composer

VOLUME ["/home/wwwroot"]
