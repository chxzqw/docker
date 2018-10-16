FROM wordpress

RUN apt update \
    && apt install -y libxml2-dev \
    && apt install -y zlib1g-dev \
    && docker-php-ext-configure soap --enable-soap \
    && docker-php-ext-install soap \
    && docker-php-ext-install zip
