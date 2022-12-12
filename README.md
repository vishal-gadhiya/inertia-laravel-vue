# Inertia.js (Laravel + Vue.js)

## Required :

PHP ^8.1

Redis

MySQL

## Installation

Clone the repo locally:

    git clone https://github.com/vishal-gadhiya/inertia-laravel-vue.git
    cd inertia-laravel-vue

Setup configuration:

    cp .env.example .env

Install PHP dependencies:

    composer install

Generate application key:

    php artisan key:generate

Install NPM dependencies:

    npm install

Build assets:

    vite / vite build

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate

Run the database seeder

    php artisan db:seed

To create the symbolic link

    php artisan storage:link

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

or you can create virtual host
