FROM php:8-fpm-alpine AS php-system-setup


# Install composer
COPY --from=composer/composer:2 /usr/bin/composer /usr/local/bin/composer
