FROM php:7.3-apache
WORKDIR /var/www/html
RUN apt update && apt install -y mariadb-server 
RUN docker-php-ext-install mysqli
RUN docker-php-ext-enable mysqli
# RUN docker-php-ext-install pdo pdo_mysql
# RUN docker-php-ext-install gd

