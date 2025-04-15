<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>

---

# 📸 Instagram Clone (Laravel + MongoDB)

## 🧠 Project Overview

A modern, full-stack **Instagram clone** built with Laravel 10 (backend) and Tailwind CSS.  
This application includes user authentication, post creation, following system, and a personalized timeline – delivering a real-world social media experience.

## ✨ Features

- 🧾 User registration, login & logout
- 🖼 Upload and display image posts
- 💬 Like and comment system
- 👥 Follow/unfollow users
- 📰 Personalized feed from followed users
- 🧪 Seeded fake data for testing

## 🛠️ Tech Stack

- **Laravel 10**
- **PHP 8.1**
- **MySQL**
- **Tailwind CSS**
- **Laravel Auth UI** for auth scaffolding
- **Vite** for frontend tooling

---

## 🚀 Installation

Clone the repo and follow these steps:

## 1. Clone the repository
```bash
  git clone https://github.com/mohamedkaram400/instagram-clone.git
```

## 2. Navigate to the project folder
```bash
cd instagram-clone
```

## 3. Install PHP dependencies
```bash
composer install
```

## 4. Copy .env and generate key
```bash
cp .env.example .env
php artisan key:generate
```

## 5. Set up your database in .env and run migrations + seed
```bash
php artisan migrate:fresh --seed
```

## 6. Install Node dependencies
```bash
npm install
```

## 7. Run frontend in dev mode
```bash
npm run dev
```

## 8. Run Laravel backend
```bash
php artisan serve
```
