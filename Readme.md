# Educational Platform

Educational Platform is a web-based learning management system built with Laravel. The project is designed to provide a structured environment for managing educational content, users, and learning processes.

## Features

* User Authentication and Authorization
* User Management (Create, Update, Delete)
* Dashboard Interface
* Image Upload Support
* Responsive User Interface
* Laravel Breeze Authentication
* Database Management with Laravel Migrations

## Technology Stack

* PHP
* Laravel
* MySQL
* Blade Templates
* Laravel Breeze
* Vite

## Installation

Clone the repository:

```bash
git clone https://github.com/tahakarami-dev/Educational-platform.git
```

Navigate to the project directory:

```bash
cd Educational-platform
```

Install dependencies:

```bash
composer install
npm install
```

Create environment file:

```bash
cp .env.example .env
```

Generate application key:

```bash
php artisan key:generate
```

Configure your database settings in the `.env` file and run migrations:

```bash
php artisan migrate
```

Start the development server:

```bash
php artisan serve
npm run dev
```

## Project Structure

* `app/` - Application core logic
* `routes/` - Application routes
* `resources/` - Views and frontend assets
* `database/` - Migrations and seeders
* `config/` - Application configuration files
* `public/` - Publicly accessible files

## License

This project is available for educational and learning purposes.
