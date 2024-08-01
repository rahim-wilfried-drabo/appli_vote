FROM php:8.0-apache

# Installer les dépendances nécessaires
RUN apt-get update && apt-get install -y libpq-dev

# Installer les extensions PHP
RUN docker-php-ext-install pdo pdo_pgsql

COPY . /var/www/html/
