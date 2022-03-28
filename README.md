# Description

This is a little implementation of a laravel 7 project as just created. Please use it to learn and play.

# Requirements

To run this project you need:

- Docker
- Docker-compose

# Instructions

1. Run `docker-compose --env-file blog/.env up -d`
2. Run `docker-compose exec app composer install`
3. Run `docker-compose exec app php artisan key:generate`
4. Check in your browser in [localhost](http://localhost:8000)
5. Modify your code in the blog folder


License: MIT
