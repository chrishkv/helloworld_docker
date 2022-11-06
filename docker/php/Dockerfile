FROM php:8.1-fpm

RUN apt-get update && \
    apt-get install -y openssl \
    zip \
    unzip \
    git \
    curl \
    libzip-dev \
    libonig-dev \
    libicu-dev \
    autoconf \
    pkg-config \
    libssl-dev
RUN docker-php-ext-install bcmath mbstring intl opcache pdo pdo_mysql mysqli