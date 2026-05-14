# 🌸 JOOD — Online Perfume Store

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-13.9.0-red?style=flat-square&logo=laravel" alt="Laravel">
  <img src="https://img.shields.io/badge/PHP-16.2%25-blue?style=flat-square&logo=php" alt="PHP">
  <img src="https://img.shields.io/badge/Blade-77%25-orange?style=flat-square" alt="Blade">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
</p>

---

## 📖 About The Project

**JOOD** is a full-featured online perfume store designed to make shopping easy and enjoyable. It provides elegant and user-friendly interfaces that allow customers to browse a wide collection of perfumes, choose their favorite products, and complete their purchases effortlessly.

**Developed by:** Eng. Maram Fadel

---

## ✨ Features

- 🛍️ **Product Browsing** — View perfume collections with images, descriptions, and prices
- 🔍 **Search & Filter** — Find perfumes by type, brand, or price range
- 🛒 **Shopping Cart** — Add and remove products with ease
- 💳 **Order Checkout** — Smooth and secure purchase process
- 👤 **Account Management** — Register, login, and track your orders
- 🔐 **Admin Dashboard** — Manage products, orders, and customers
- 📱 **Responsive Design** — Works on all devices (mobile, tablet, desktop)

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **Laravel** | Main backend framework |
| **Blade** | Templating engine for UI |
| **PHP** | Core programming language |
| **MySQL** | Database |
| **SCSS / CSS** | Styling and UI design |
| **JavaScript** | Frontend interactivity |

---

## 🚀 Getting Started

### Prerequisites

- PHP >= 8.1
- Composer
- MySQL
- Node.js & NPM

### Installation

```bash
# Clone the repository
git clone https://github.com/m4aram/JOOD_web.git

# Navigate to the project directory
cd JOOD_web

# Install PHP dependencies
composer install

# Install JavaScript dependencies
npm install

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Set up your database in .env then run:
php artisan migrate

# (Optional) Seed sample data
php artisan db:seed

# Start the development server
php artisan serve
```

Open your browser at: `http://localhost:8000`

---

## 📁 Project Structure

```
JOOD_web/
├── app/
│   ├── Http/Controllers/    # Store controllers
│   └── Models/              # Product and order models
├── resources/
│   └── views/               # Blade UI templates
├── routes/
│   └── web.php              # Application routes
├── database/
│   └── migrations/          # Database tables
└── public/                  # Public assets
```

---

## 👩‍💻 Developer

**Eng. Maram Fadel** — Mobile App & Web Developer

[![GitHub](https://img.shields.io/badge/GitHub-m4aram-black?style=flat-square&logo=github)](https://github.com/m4aram)

---

## 📄 License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

<p align="center">Made with ❤️ using Laravel</p>
