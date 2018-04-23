<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

# Food Ordering RESTful API
This is a [Laravel Framework](https://laravel.com/) Application.

## Prerequisites
Make sure you have [PHP, MySQL, Apache](https://www.apachefriends.org/pt_br/index.html) and [Composer](https://getcomposer.org/) installed.


## Installing
- Clone this repository:
```
git clone https://github.com/jsy15214/myapp.git
```
- Access directory:
```
cd myapp
```
- Install dependencies:
```
composer install
```
- Create a copy of *.env.example* and rename to *.env*;

- Generate Laravel App Key:
```
php artisan key:generate
```


## Setting Database
- Create database;

- Insert into *.env*: database, user and password;

- Create tables and seed database:
```
php artisan migrate:refresh --seed
```


## Running
- Serve the app:
```
php artisan serve
```

Head to http://localhost:8000 in your browser and you'll see the app running.

You can also test endpoints with [Postman](https://www.getpostman.com/).

## User Instructions
Please view full instructions in *instructions.pdf* in the current directory. Enjoy!

## References
https://github.com/90lucasgabriel/restaurant-api/blob/master/README.md
