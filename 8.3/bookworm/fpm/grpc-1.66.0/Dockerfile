FROM php:8.3-fpm-bookworm

RUN apt-get update \
    && apt-get install -y libzip-dev \
    && pecl install grpc-1.66.0 \
    && rm -rf /var/lib/apt/lists/*
