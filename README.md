## Book Rent Laravel 9 Project

This is a simple Book Rent application built with Laravel 9 and MySQL.

## 📌 Table of Contents

    Introduction
    Features
    Requirements
    Setup Instructions
    Running the Application
    Testing
    License

## ✨ Introduction

This project is a simple Book Rental Management System designed to manage book rentals with ease using Laravel 9 as the framework and MySQL as the database.

## 🚀 Features

    Book catalog system with search & filter options.
    Book renting functionality.
    User authentication.
    Responsive design with frontend integration using Laravel Mix.

## 🛠️ Requirements

Before starting, ensure you have the following tools installed:

    PHP >= 8.0
    Composer
    Node.js & npm
    MySQL Database
    Laravel 9 dependencies
    A code editor (e.g., VS Code)

## ⚙️ Setup Instructions
## 1. Clone the Repository

First, clone the repository to your local machine:
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
## 2. Set Up Your Environment Variables

Copy the example .env file:
```bash
cp .env.example .env
```
Open .env and configure your database settings:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password
```

## 3. Install Dependencies
Using Composer:

Install the PHP dependencies:
```bash
composer install
```
Using npm:

Install frontend dependencies:
```bash
npm install
```
## 4. Generate the Application Key

Generate the application key:
```bash
php artisan key:generate
```
## 5. Run Migrations

Run database migrations:
```bash
php artisan migrate
```
## 6. Seed the Database (Optional)

If you have seeders, run:
```bash
php artisan db:seed
```
## 🏃‍♀️ Running the Application
Start the Local Development Server:
```bash
php artisan serve
```
This will serve your application at http://localhost:8000.
Run Frontend Watch:

In a separate terminal window, run:
```bash
npm run dev
```
This will compile assets like JavaScript and CSS changes.
🧪 ## Testing

To run tests, you can use PHPUnit:
```bash
./vendor/bin/phpunit
```
## 📄 License

This project is licensed under the [MIT license](https://opensource.org/licenses/MIT). Feel free to fork and make changes as you need.
## 🛠️ Troubleshooting

    Dependency installation issue?
    Make sure Node.js and npm are correctly installed. Re-run npm install.

    Database connection error?
    Double-check your .env file for correct database credentials.

    Laravel server not running?
    Use php artisan serve to ensure the application is hosted properly.

If you find any issues or need to contribute, feel free to open a GitHub Issue.
