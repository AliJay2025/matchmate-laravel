<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# MatchMate - Football League Management System

A Laravel-based web application for managing local football leagues, teams, players, fixtures, and results.

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- Simple, fast routing engine.
- Powerful dependency injection container.
- Multiple back-ends for session and cache storage.
- Expressive, intuitive database ORM.
- Database agnostic schema migrations.
- Robust background job processing.
- Real-time event broadcasting.

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Project Features

- User authentication with roles (Admin, Manager, Fan)
- Team management (Create, Read, Update, Delete)
- Player management with team-specific access
- Fixture scheduling and result reporting
- Live league table generation
- Responsive Bootstrap UI
- Client-side and server-side validation

## Requirements

- PHP >= 8.1
- MySQL >= 5.7
- Composer
- Node.js & NPM

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/AliJay2025/matchmate-laravel.git
cd matchmate-laravel

2. Install PHP dependencies

bash
composer install
3. Set up environment file

bash
cp .env.example .env
php artisan key:generate
4. Configure database in .env

env
DB_DATABASE=matchmate
DB_USERNAME=root
DB_PASSWORD=your_password
5. Create database

bash
mysql -u root -p -e "CREATE DATABASE matchmate;"
6. Run migrations

bash
php artisan migrate
7. Install NPM dependencies

bash
npm install
npm run build
8. Start the application

bash
php artisan serve
9. Access the application
Open browser: http://localhost:8000

Project Team
Name	Role
Ali Jabriil	Developer
Abdihafid Gahayr	Developer
Abdirahman Farah	Developer