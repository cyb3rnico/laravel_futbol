<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

#### Crear la base de datos en phpMyAdmin (XAMPP)
- dow020_futbol

### Clonar el repositorio

#### En la terminal del proyecto Laravel ejecutar los siguientes comandos:

#### Bajar las dependencias del proyecto
- composer install

#### Crear el .env
- cp .env.example .env
(Editar archivo con su respectiva base de datos a asociar - dow020_futbol).

#### Generar la clave
- php artisan key:generate

#### Ejecutar las migraciones
- php artisan migrate

#### Correr el servicio localmente
- php artisan serve

#### Correr el servicio para todas las IP
- php artisan serve --host 0.0.0.0

### Poblar la base de datos con roles y usuarios
- php artisan db:seed

### Para probar el sistema
- Con el navegador ir a http://127.0.0.1:8000/

### Iniciar sesión con las credenciales
###### Usuario Administrador
- email: admin@gmail.com
- password: 1234
###### Usuario Coordinador
- email: coordinador@gmail.com
- password: 5678


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
