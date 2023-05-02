<p align="center"><a href="https://twitter.com/mokammeltanvir" target="_blank"><img src="https://avatars.githubusercontent.com/u/50278?s=200&v=4" width="200" alt="Twitter Logo"></a></p>

# Twitter-Clone

Twitter clone project using Laravel 10, Vue 3, Tailwind CSS, and Laravel Breeze.

## Run Locally

Clone the project

```bash
  https://github.com/mokammeltanvir/Twitter-Clone.git
```

Go to the project directory

```bash
  cd Twitter-Clone
```

Install dependencies

```bash
composer install

cp .env.example .env

php artisan key:generate

composer require laravel/breeze --dev

php artisan breeze:install vue --ssr
```

Create the DB

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel_twitter
DB_USERNAME=root
DB_PASSWORD=
```

migrate your DB

```bash
php artisan migrate

php artisan db:seed
```

Start the Server

```bash
php artisan serve
```

## Application Screenshots

![App Screenshot](https://raw.githubusercontent.com/mokammeltanvir/Twitter-Clone/main/twitter-clone.png)

