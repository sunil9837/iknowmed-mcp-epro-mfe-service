# Use PHP 8.0 base image
FROM php:8.2-cli

# Install SQLite extension for PHP 8
# RUN docker-php-ext-install pdo pdo_sqlite

COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
# Expose port 8080
EXPOSE 8080
COPY . .
# Command to run PHP server
CMD [ "php", "-S", "0.0.0.0:8080" ]

