## CREATE NEW PROJECT LARAVEL

1. `docker-compose build`
2. `docker-compose up`

Lo siguiente es: desde otra terminal crear el proyecto laravel usando el comando que sigue
`docker-compose run --rm composer create-project laravel/laravel .  `
Esto creara un proyecto laravel en la carpeta src

## ARTISAN 
* `docker-compose run --rm artisan config:cache` ==> ELIMINAR LA CACHE CON ARTISAN 
* `docker-compose run --rm artisan install:api` ==> ARTISAN ISNTALL API
* `docker-compose run --rm artisan make:migration create_productos_table` ==> CREAR MIGRACIONES 
* `docker-compose run --rm artisan migrate` ==> EJECUTAR MIGRACIONES 
* `docker-compose run --rm artisan make:model Productos` ==> CREAR UN MODELO 
* `docker-compose run --rm artisan make:controller ProductosController --resource` ==> CREAR UN CONTROLADOR
* `docker-compose run --rm artisan route:list` ==> LISTADO DE RUTAS