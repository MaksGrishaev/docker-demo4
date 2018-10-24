FROM php:7.0-apache

RUN apt-get update

RUN docker-php-ext-install mysqli pdo_mysql mcrypt

RUN apt-get -y install libsqlite3-dev libsqlite3-0 mysql-client
