<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

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
```bash
php -v
Si no lo tienes, descárgalo aquí: https://www.php.net/downloads.php

🔹 Paso 2: Instalar Composer (v2.8.8)
Opción 1: Instalar Composer con comandos
bash
Copiar código
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php composer-setup.php
php -r "unlink('composer-setup.php');"
Luego, mueve Composer a una ubicación global:

bash
Copiar código
mv composer.phar /usr/local/bin/composer
Opción 2: Instalar Composer con gestor de paquetes
Consulta la guía oficial: https://getcomposer.org/download

Verifica la instalación:

bash
Copiar código
composer -V
🔹 Paso 3: Crear Proyecto con Laravel 10.3.3
Opción 1: Última versión de Laravel 10.x
bash
Copiar código
composer create-project laravel/laravel nombre-del-proyecto
Opción 2: Versión exacta Laravel 10.3.3
bash
Copiar código
composer create-project laravel/laravel="10.3.3" nombre-del-proyecto
🔹 Paso 4: Probar el Proyecto
Entra a tu carpeta y ejecuta el servidor de desarrollo:

bash
Copiar código
cd nombre-del-proyecto
php artisan serve
Abre en tu navegador:
http://127.0.0.1:8000

🔧 Comandos Rápidos de Composer
Instalar dependencias:

bash
Copiar código
php composer.phar install
Instalar Laravel:

bash
Copiar código
composer create-project laravel/laravel nombre-del-proyecto
📚 Recursos de Aprendizaje
Documentación oficial de PHP

Documentación oficial de Composer

Documentación oficial de Laravel

Laravel Bootcamp

📝 Notas
Todos los pasos están probados en PHP 8.1.32, Composer 2.8.8 y Laravel 10.3.3.

Asegúrate de tener conexión a internet y permisos de administrador al mover Composer a /usr/local/bin/.

yaml
Copiar código

---

📌 **Qué incluye este README:**
- Pasos numerados y ordenados (PHP → Composer → Laravel).  
- Comandos claros con bloques de código.  
- Enlaces oficiales destacados.  
- Opción de instalar versiones exactas.  
- Sección de notas y recursos de aprendizaje.  

---

¿Quieres que le agregue también una **sección de pasos para subir el proyecto a GitHub (git init, add, commit, push)** al final?