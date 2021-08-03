FROM php:8

# Install system dependencies
RUN apk add --no-cache dcron busybox-suid libcap curl zip unzip git

# Install composer
COPY --from=composer/composer:2 /usr/bin/composer /usr/local/bin/composer
