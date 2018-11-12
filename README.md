# Geechs Project

## Features

- Laravel 5.6 
- Vue + VueRouter + Vuex
- Pages with dynamic import and custom layouts
- Login, register and password reset
- Authentication with Laravel Passport https://laravel.com/docs/5.7/passport#introduction
- Bootstrap 4

## Installation

- Edit `.env` and set your database connection details
- `composer install`
- `php artisan key:generate`
- `php artisan migrate`
- `yarn` / `npm install`
- `php artisan passport:install`

## Usage

#### Development

```bash
# build and watch
npm run watch

# serve with hot reloading
npm run hot
```

#### Production

```bash
npm run production
```