FROM mcr.microsoft.com/devcontainers/php:8.3

# Install ekstensi penting untuk Laravel + Filament
RUN apt-get update && \
    apt-get install -y \
        php-intl \
        php-xdebug \
        sqlite3 \
    && rm -rf /var/lib/apt/lists/*
