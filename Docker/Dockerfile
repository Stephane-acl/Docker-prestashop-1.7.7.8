FROM prestashop/prestashop-git:7

RUN docker-php-ext-install mysqli pdo pdo_mysql

RUN a2enmod headers && service apache2 restart
