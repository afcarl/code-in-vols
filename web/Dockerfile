FROM php:5-apache
RUN sed -i "s,/var/www/html,/code/web," /etc/apache2/sites-available/*.conf /etc/apache2/*.conf
RUN sed -i "s,/var/www,/code/web," /etc/apache2/sites-available/*.conf /etc/apache2/*.conf

