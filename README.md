# Contao example bundle

Contao example bundle as template for new bundles.

## Install composer packages
    docker run -it --rm \
    -v ".:/var/www/html" \
    laemmi/php-fpm:8.1 \
    composer install


## Run php codesniffer
    docker run -it --rm \
    -v ".:/var/www/html" \
    laemmi/php-fpm:8.1 \
    vendor/bin/phpcs

## Run autofix with PHP Code Beautifier and Fixer
    docker run -it --rm \
    -v ".:/var/www/html" \
    laemmi/php-fpm:8.1 \
    vendor/bin/phpcbf