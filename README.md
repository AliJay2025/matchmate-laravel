
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# MatchMate - Football League Management System

A Laravel-based web application for managing local football leagues, teams, players, fixtures, and results.

## Installation

**1. Clone the repository**
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