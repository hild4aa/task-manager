# Task Manager Laravel
# 📋 Task Manager App

A simple task manager web app built with Laravel. Users can register, login, create, manage, and track their daily tasks with completion statistics.

## 🚀 Features

- User authentication (register/login)
- CRUD tasks (create, read, update, delete)
- Mark tasks as done
- Task filtering and sorting
- Dashboard with completion stats
- RESTful API endpoints
- Responsive UI with Bootstrap/Tailwind

## 🛠️ Tech Stack

- PHP 8.x
- Laravel 10
- MySQL (via Laragon)
- Tailwind CSS / Bootstrap
- Chart.js (for dashboard)

## 🔧 Installation

```bash
git clone https://github.com/username/task-manager.git
cd task-manager
composer install
cp .env.example .env
php artisan key:generate
# Atur database di .env (DB_DATABASE, DB_USERNAME, DB_PASSWORD)
php artisan migrate --seed
php artisan serve
