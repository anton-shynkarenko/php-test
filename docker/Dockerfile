FROM php:8.1
RUN apt update && apt install -y \
    mc \
    git \
    && \
    php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" && \
    php composer-setup.php --install-dir=/bin --filename=composer