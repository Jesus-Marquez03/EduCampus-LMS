# Guía de instalación

Esta guía explica cómo instalar y ejecutar EduCampus LMS en tu computador de forma local.

## Requisitos

Para que el proyecto funcione necesitas tener instalado lo siguiente:

- Node.js (versión 18 o mayor)
- PHP 8.1
- Composer
- MySQL o PostgreSQL
- Git

## Base de datos

Primero hay que crear la base de datos. Se puede hacer desde la terminal o desde
una herramienta como TablePlus o phpMyAdmin.

El nombre de la base de datos debe ser: educampus_db

## Variables de entorno

Hay que copiar el archivo .env.example y renombrarlo como .env.
Dentro de ese archivo se cambian estos valores:

DB_HOST=localhost
DB_DATABASE=educampus_db
DB_USERNAME=tu_usuario
DB_PASSWORD=tu_contraseña

## Cómo ejecutar el proyecto

1. Clona el repositorio con: git clone <url>
2. Entra a la carpeta del proyecto
3. Instala las dependencias con npm install o composer install
4. Corre las migraciones con: php artisan migrate
5. Inicia el servidor con: php artisan serve

## Verificación

Si todo salió bien, abre el navegador y entra a http://localhost:8000.
Deberías ver la pantalla de inicio del sistema.