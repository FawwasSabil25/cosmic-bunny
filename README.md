# Cosmic Bunny

A digital game e-commerce web app, inspired by other game stores. Built as a team project for the Web Programming Practicum course (Universitas Pasundan).

**Live demo:** https://cosmic-bunny.rezaa.me/ [VERIFY it loads]

## Features

- User registration and login
- Role-based access: customers and admins
- Browse games and categories
- Admin management of games and categories (CRUD)
- Cart, checkout, and transaction records

## Tech stack

- Laravel (PHP), MySQL
- JWT authentication, role-based access control
- Blade templates, Tailwind CSS, Vite

## My contributions (Backend)

- Login and register system
- CRUD for games and categories
- Buying process: cart, checkout, and transactions
- Database schema
- Middlewares and admin system

## Getting started

Requirements: PHP, Composer, Node.js, MySQL.

```bash
git clone https://github.com/FawwasSabil25/cosmic-bunny.git   # [VERIFY repo URL]
cd cosmic-bunny
composer install
npm install
cp .env.example .env        # then set your database credentials
php artisan key:generate
php artisan migrate
php artisan jwt:secret      # [VERIFY: only if the project uses tymon/jwt-auth]
npm run dev                 # in one terminal
php artisan serve           # in another terminal
```

## Team

Built collaboratively by a team covering frontend, backend, and UI/UX design.
Original repository: https://github.com/rezaageng/cosmic-bunny

## Screenshots

[PLACEHOLDER: add 2-3 screenshots, e.g. home page, cart, admin panel]
