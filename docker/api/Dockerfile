FROM php:8-fpm

WORKDIR /var/www

# install new PHP extensions
RUN docker-php-ext-install pdo pdo_mysql

# override custom configs
COPY xdebug.ini $PHP_INI_DIR/conf.d/