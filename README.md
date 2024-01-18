<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Document management system

This system can manage various types of documents.

## Installation

Clone the Repository:

```bash
  git clone <repository-url>
```

Navigate into the cloned project directory:

```bash
  cd <project-name>
```

Install the required Composer dependencies:

```bash
  composer install
```

Create a copy of the .env.example file and rename it to .env. Then configure env file using you database information:

Generate Application Key:

```bash
  php artisan key:generate
```

Migrate Database

```bash
  php artisan migrate
```

Seed Database:

```bash
  php artisan migrate --seed
  or
  php artisan db:seed
```

Start the Development Server:

```bash
  php artisan serve
```
