<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="130" alt="Laravel">
  </a>
  &nbsp;&nbsp;
  <a href="https://www.php.net/" target="_blank">
    <img src="https://www.php.net/images/logos/php-logo.svg" width="90" alt="PHP">
  </a>
  &nbsp;&nbsp;
  <a href="https://git-scm.com/" target="_blank">
    <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.svg" width="90" alt="Git">
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/" target="_blank">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="90" alt="GitHub">
  </a>
  &nbsp;&nbsp;
  <a href="https://getcomposer.org/" target="_blank">
    <img src="https://getcomposer.org/img/logo-composer-transparent2.png" width="90" alt="Composer">
  </a>
  &nbsp;&nbsp;
  <a href="https://code.visualstudio.com/" target="_blank">
    <img src="https://code.visualstudio.com/assets/images/code-stable.png" width="90" alt="Visual Studio Code">
  </a>
</p>

---

# Proyecto Laravel 10.3.3
## _Universidad Adventista de Bolivia_  
### Taller de Programación  

---

## 📌 Introducción
Este proyecto documenta **cómo configurar un entorno de desarrollo Laravel 10.3.3** desde cero, usando:  

- **PHP 8.1.32**
- **Composer 2.8.8**
- **Laravel 10.3.3**
- **Git & GitHub**
- **Visual Studio Code**

💡 Esta guía está diseñada para estudiantes y desarrolladores que deseen instalar Laravel de manera correcta y profesional.

---

## 🔥 Características

- Configuración completa del entorno PHP + Composer.
- Instalación de Laravel en versión exacta 10.3.3.
- Comandos Artisan para desarrollo ágil.
- Preparado para conexión con **GitHub**.
- Compatible con Windows, Linux y macOS.


---


## 🎯 Objetivo  
Familiarizarse con el proceso de instalación de **Composer**, **PHP** y **Laravel**, practicando los pasos básicos para configurar el entorno de desarrollo.  

---
## 📚 Prerrequisitos

| Herramienta | Descripción | Link |
| ----------- | ----------- | ---- |
| PHP 8.1.32+ | Lenguaje base del proyecto | [Descargar](https://www.php.net/downloads.php) |
| Composer 2.8.8 | Gestor de dependencias PHP | [Descargar](https://getcomposer.org/download) |
| Laravel 10.3.3 | Framework backend | [Laravel Docs](https://laravel.com/docs/10.x) |
| Git & GitHub | Control de versiones | [Git](https://git-scm.com) / [GitHub](https://github.com) |
| Visual Studio Code | Editor recomendado | [VSCode](https://code.visualstudio.com) |

---

# 🛠️ Instalación Paso a Paso

## 🔹 Paso 1: Verificar PHP

php -v
Si no está instalado, descárgalo aquí:
➡️ https://www.php.net/downloads.php


## 🔹 Paso 2: Instalar Composer (v2.8.8)
Opción 1 - Manual con comandos

### Copiar código
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php composer-setup.php
php -r "unlink('composer-setup.php');"
mv composer.phar /usr/local/bin/composer
Verificar instalación


### Copiar código
composer -V
Opción 2 - Usar instalador oficial
         - php composer.phar install
➡️ https://getcomposer.org/download


## 🔹 Paso 3: Instalar Laravel
Última versión Laravel 10.x
### Copiar código
composer create-project laravel/laravel nombre-del-proyecto
Versión exacta Laravel 10.3.3
### Copiar código
composer create-project laravel/laravel="10.3.3" nombre-del-proyecto

## 🔹 Paso 4: Ejecutar el Servidor de Desarrollo
### Copiar código
cd nombre-del-proyecto
php artisan serve
Abrir en el navegador:
➡️ http://127.0.0.1:8000

### 🚀 Comandos Rápidos
Acción	Comando
Instalar dependencias	composer install
Limpiar caché de Laravel	php artisan cache:clear
Generar key del proyecto	php artisan key:generate
Migrar base de datos	php artisan migrate

### 🔗 Recursos Oficiales
### 📖 Documentación Laravel

### 🐘 Documentación PHP

### 📦 Composer Docs

### 🌐 Laravel Bootcamp

### 📂 Subir Proyecto a GitHub

# Copiar código
git init
git add .
git commit -m "Proyecto Laravel 10.3.3 listo"
git branch -M main
git remote add origin https://github.com/usuario/nombre-repo.git
git push -u origin main
### 📝 Notas
Probado en PHP 8.1.32, Composer 2.8.8, Laravel 10.3.3.

Se recomienda usar VS Code con extensiones de Laravel.

Mantén conexión estable a Internet al instalar dependencias.

### 📜 Licencia
MIT - Software Libre para Aprendizaje

yaml
Copiar código

---


 
 


