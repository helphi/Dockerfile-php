FROM php:5.6.33-apache-jessie

RUN apt-get update -y &&\
  apt-get install -y libxml2-dev &&\
  apt-get clean -y
RUN docker-php-ext-install mysql soap
