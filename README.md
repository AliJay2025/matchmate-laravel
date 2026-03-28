# MatchMate - Football League Management System

A Laravel-based web application for managing local football leagues, teams, players, fixtures, and results.

## Installation

**1. Clone the repository**
```
git clone https://github.com/AliJay2025/matchmate-laravel.git
cd matchmate-laravel
```

**2. Install PHP dependencies**
```
composer install
```

**3. Set up environment file**
```
cp .env.example .env
php artisan key:generate
```

**4. Configure database in .env**
```
DB_DATABASE=matchmate
DB_USERNAME=root
DB_PASSWORD=your_password
```

**5. Create database**
```
mysql -u root -p -e "CREATE DATABASE matchmate;"
```

**6. Run migrations**
```
php artisan migrate
```

**7. Install NPM dependencies**
```
npm install
npm run build
```

**8. Start the application**
```
php artisan serve
```

**9. Access the application**
Open browser: http://localhost:8000

## Project Team

| Name | Role |
|------|------|
| **Ali Jabriil** | Developer |
| **Abdihafid Gahayr** | Developer |
| **Abdirahman Farah** | Developer |
