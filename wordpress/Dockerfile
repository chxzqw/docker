FROM wordpress:latest

RUN apt update \
    && apt install libxml2-dev -y \
    && docker-php-ext-configure soap --enable-soap \
    && docker-php-ext-install soap
