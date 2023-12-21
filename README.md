# This is Template
## Description
Build PHP, nginx and Redis Development environment on Docker

## Usage
```bash
cd init
docker compose up -d --build
docker compose exec php-init bash

// If you create a Laravel project, make it laravel/laravel!
composer create-project --prefer-dist laravel/lumen /var/www/html/
composer require --dev friendsofphp/php-cs-fixer
touch .php-cs-fixer.dist.php
composer require --dev phpstan/phpstan phpstan/extension-installer

// complete initialized!!!
```
