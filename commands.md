## Commands

### Laravel
1. Preparación y limpieza de proyecto Laravel `php artisan config:cache && php artisan cache:clear && php artisan view:clear && php artisan config:clear`

### Docker
1. Run composer from container `docker run --rm -it --volume $(pwd):/app prooph/composer:8.0 [your composer command]`
2. Alternative for last command `docker run --rm -v $(pwd):/app composer install`
3. Stop and restart a docker container witouth cache `docker compose down && docker compose build --no-cache && docker compose up -d`
