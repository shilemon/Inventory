<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400">
  </a>
</p>

<h1 align="center">Inventory Management System</h1>
<hr>

## 🧰 Quick Installation

```bash
git clone https://github.com/ekramasif/Inventory_Management_System.git
cd Inventory_Management_System
```

### 📦 Composer

```bash
composer update
```

### 🛠️ Environment Variable Setup

```bash
cp .env.example .env
```

### 🗄️ Migration Table in Database

> ⚠️ Create a database named `IMS` before running the migration.

```bash
php artisan migrate
```

### 🔌 Run Local Development Server

```bash
php artisan serve
```

> URL: http://127.0.0.1:8000/

---

## 🚀 Production Deployment (Docker + AWS + CI/CD)

This Laravel project is fully containerized and deployed using modern DevOps practices.

### ✅ Deployment Stack

- 🐳 Docker & Docker Compose
- ☁️ AWS EC2 Ubuntu Server
- ⚙️ GitHub Actions for CI/CD
- 🔐 Laravel `.env` auto setup & key generation
- 🐘 MySQL 8 with phpMyAdmin via Docker

### 🌍 Live Server

> http://54.179.155.20/

### 🔄 GitHub Actions Workflow

- Triggers on push to `main`
- Builds Laravel Docker image
- Connects to AWS EC2 via SSH
- Replaces running containers
- Runs database migrations

### 📂 Project Includes

- `Dockerfile` for Laravel app
- `docker-compose.yml` for Laravel, MySQL, phpMyAdmin
- `.github/workflows/deploy.yml` for CI/CD automation

### 🛠 Technologies Used

- Laravel 10+
- PHP 8.2+
- MySQL 8
- Docker
- GitHub Actions
- AWS EC2 (Ubuntu 22.04)

---

