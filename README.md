<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## # Laravel 9
Introducción a las bases de Laravel 9

# Laravel 9

Laravel en version 9.2.0

Revisión de las bases de la Laravel 9 desde cero, el framework para PHP más popular de la actualidad mediante una introducción básica.

Este proyecto se trabaja desde un servidor local basado en el sistema operativo Debian 11 con version del Kernel 5.10.103 x86_64, con apache 2/2.4.52 y PHP/v.8.1.3 instalado.


# Resumen:
Laravel 9 es el framework para PHP más popular hoy en la actualidad y en la ultima versión estable. Es uno de los frameworks más populares para desarrollar aplicaciones modernas y escalables en el lado del servidor con PHP, ya sea para ser desarrollador back-end o full-stack, o incluso si ya se dedicaa al desarrollo web, es casi obligatorio aprender Laravel 5.

Laravel 5 es un framework muy solicitado por las empresas, fácil de aprender y muy útil. Utiliza componentes de frameworks tan potentes y robustos como Symfony

Esta introducción ayudara a usar de manera inicial como instalar Laravel 5 y trabajar con las rutas, vistas y plantillas de Laravel, se podra trabajar con el sistema de plantillas blade, conoceremos varios conceptos teóricos y poder estar preparado para seguir avanzando con este entorno de trabajo.

Se tratan los aspectos más básicos y fundamentales paso a paso y desde cero, por tanto no es necesario saber nada de Laravel para aprender a usarlo, aunque si será necesario saber HTML y PHP 

Soy desarrollador web en una empresa y llevo inmerso en el mundo de la programación y la informática desde los 22 años.

Me encanta programar y todo lo relacionado con Internet y las nuevas tecnologías, crear cosas y compartir a los demás.

Aspectos:
Instalacion y primeros pasos
Instalar Laravel
Desde cero incluso una version concreta.
Crear host virtuales en apache
Estructura de un proyecto en Larevel
Rutas, utilidades y vistas
Interfaz de lineas de comandos 
Trabajar con las vistas
Plantillas blade de Laravel
Imprimir variables, bucles, plantillas maestras, secciones de plantillas y susticion de contenido.


## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


# Export - Import Proyect

Al hacer la clonación del proyecto en un servidor local, aun cumpliendo los requisitos de origen instalados, sule presentarse un error como se describe a continuación.

Incluso suele suceder cuando se pasa de un proyecto a otro de computadora a computadora.

Aun instalado composer y laravel, cuando se inetenta abrir incluso mediante php artisan serve, en la direccion del proyecto en htdocs en xampp/wamp/appserv manda unos errores como los siguientes:

Warning: require(C:\Appserv\htdocs\LaravelProyect\public/../../laravel/bootstrap/autoload.php): failed to open stream: No such file or directory in C:\Appserv\htdocs\LaravelProyect\public\index.php on line 34

Fatal error: require(): Failed opening required 'C:\Appserv\htdocs\LaravelProyect\public/../../laravel/bootstrap/autoload.php' (include_path='C:\Appserv\php\PEAR') in C:\Appserv\htdocs\LaravelProyect\public\index.php on line 34

si se esta manejando un proyecto desde un servidor como XAMPP/WAMP/Appserv, no es necesario utilizar la sentencia php artisan serve; puesto que se tiene un servidor local Apache corriendo y se podrá acceder al proyecto desde el navegador accesando a la ruta publica o bien con la configuración del Virtual Host configurado.

ahora bien.


Esos mensajes de error es porque no ha instalado las librerias correspondientes,

1. Ejecuta en la raiz de tu proyecto

	composer install

	ej.
		cd /var/www/html/dev/laravel/
		composer install

2. Seguido tendrás que copiar el archivo '.env.example' a '.env'

		cp .env.example .env

3. Luego ejecutar

		php artisan key:generate

4. Configurar la conexión a la base de datos.

	php artisan migrate (si tiene seeders utiliza  --seed)

5. Visualizar al proyecto desde la ruta adecuada en el navegador.


