FROM php:7.2-apache
COPY php.ini /usr/local/etc/php/
RUN cp /etc/apache2/mods-available/rewrite.load /etc/apache2/mods-enabled/rewrite.load
# RUN apt-get update \
#   && apt-get install -y libfreetype6-dev libjpeg62-turbo-dev libpng-dev \
#   && pecl install mcrypt \
#   && docker-php-ext-install pdo_mysql mysqli mbstring gd iconv \
#   && docker-php-ext-enable mcrypt
