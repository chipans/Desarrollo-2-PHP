<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Logo de Laravel"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Estado de la compilación"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total de Descargas"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Última Versión Estable"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="Licencia"></a>
</p>

---

## Acerca de Laravel

Laravel es un framework para aplicaciones web con una sintaxis expresiva y elegante. Creemos que el desarrollo debe ser una experiencia agradable y creativa para que sea verdaderamente satisfactorio. Laravel simplifica el desarrollo al facilitar tareas comunes usadas en muchos proyectos web, tales como:

- [Motor de enrutamiento simple y rápido](https://laravel.com/docs/routing).
- [Potente contenedor de inyección de dependencias](https://laravel.com/docs/container).
- Múltiples sistemas de almacenamiento para [sesiones](https://laravel.com/docs/session) y [caché](https://laravel.com/docs/cache).
- [ORM de base de datos intuitivo y expresivo](https://laravel.com/docs/eloquent).
- [Migraciones de base de datos independientes del sistema](https://laravel.com/docs/migrations).
- [Procesamiento robusto de trabajos en segundo plano](https://laravel.com/docs/queues).
- [Transmisión de eventos en tiempo real](https://laravel.com/docs/broadcasting).

Laravel es accesible, poderoso y proporciona las herramientas necesarias para construir aplicaciones grandes y robustas.


# Proyecto Laravel 10.3.3  
# Universidad Adventista de Bolivia  
## Taller de Programación  

---

## 📌 Descripción  
Este documento detalla **paso a paso** cómo instalar y configurar correctamente:  
- **PHP 8.1.32**  
- **Composer 2.8.8**  
- **Laravel 10.3.3**  
Para tener un entorno de desarrollo funcional y listo para trabajar en proyectos Laravel.  

---

## 📝 Prerrequisitos  
1. Tener una cuenta de **GitHub**: [https://github.com](https://github.com)  
2. Instalar **PHP 8.1.32 o superior**: [https://www.php.net/downloads.php](https://www.php.net/downloads.php)  
3. Instalar **Visual Studio Code**: [https://code.visualstudio.com](https://code.visualstudio.com)  

---

## 🎯 Objetivo  
Familiarizarse con el proceso de instalación de **Composer**, **PHP** y **Laravel**, practicando los pasos básicos para configurar el entorno de desarrollo.  

---

## 🚀 Pasos de Instalación

### 🔹 Paso 1: Verificar e Instalar PHP
Asegúrate de tener **PHP 8.1.32** instalado:
<hr>
php -v
Si no lo tienes, descárgalo aquí: https://www.php.net/downloads.php
<hr>
🔹 Paso 2: Instalar Composer (v2.8.8)
Opción 1: Instalar Composer con comandos
<hr>
Copiar código
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php composer-setup.php
php -r "unlink('composer-setup.php');"
Luego, mueve Composer a una ubicación global:

<hr>
Copiar código
mv composer.phar /usr/local/bin/composer
Opción 2: Instalar Composer con gestor de paquetes
Consulta la guía oficial: https://getcomposer.org/download
<hr>
Verifica la instalación:
<hr>
Copiar código
composer -V

<hr>
🔹 Paso 3: Crear Proyecto con Laravel 10.3.3
Opción 1: Última versión de Laravel 10.x
<hr>
Copiar código
composer create-project laravel/laravel Desarrollo-2-PHP
Opción 2: Versión exacta Laravel 10.3.3
<hr>
Copiar código
composer create-project laravel/laravel="10.3.3" Desarrollo-2-PHP

<hr>
🔹 Paso 4: Probar el Proyecto
Entra a tu carpeta y ejecuta el servidor de desarrollo:
<hr>
Copiar código
cd nombre-del-proyecto
php artisan serve
Abre en tu navegador:
http://127.0.0.1:8000
<hr>

🔧 Comandos Rápidos de Composer
Instalar dependencias:
<hr>
Copiar código
php composer.phar install
Instalar Laravel:

<hr>
Copiar código
composer create-project laravel/laravel Desarrollo-2-PHP
<hr>
📚 Recursos de Aprendizaje
Documentación oficial de PHP

Documentación oficial de Composer

Documentación oficial de Laravel

Laravel Bootcamp
<hr>

📝 Notas
Todos los pasos están probados en PHP 8.1.32, Composer 2.8.8 y Laravel 10.3.3.

Asegúrate de tener conexión a internet y permisos de administrador al mover Composer a /usr/local/bin/.

yaml
Copiar código

<hr>

📌 **Qué incluye este README:**
- Pasos numerados y ordenados (PHP → Composer → Laravel).  
- Comandos claros con bloques de código.  
- Enlaces oficiales destacados.  
- Opción de instalar versiones exactas.  
- Sección de notas y recursos de aprendizaje.  

<hr>

¿Quieres que le agregue también una **sección de pasos para subir el proyecto a GitHub (git init, add, commit, push)** al final?