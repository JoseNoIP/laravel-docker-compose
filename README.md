# laravel-docker-compose

1. Clonar este repositorio
2. Clonar el repositorio de la applicación Laravel dentro de laravelApp
3. Crear archivo .env con base en .env.sample
4. Ejecutar docker-compose up -d
5. Ejecutar artisan y composer con el contenedor 'app', ejemplo: "docker exec app composer install", "docker exec app php artisan migrate"