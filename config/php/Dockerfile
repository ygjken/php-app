FROM php:7.4-apache
COPY ./php.ini /usr/local/etc/php/php.ini
COPY ./apache2.conf /etc/apache2/apache2.conf

ARG WORKDIR=/var/www/html
WORKDIR ${WORKDIR}
