### API with JWT (with Laravel Passport) Authentication Boilerplate with Laravel v6.2

#### System Requirements

PHP >=7.2 (Newer is Better)

#### How to Install

1. run `composer install`
2. run `cp .env.example .env`
3. fill the database credential of `.env`
4. run `php artisan key:generate`
5. run `php artisan migrate`
6. run `php artisan passport:install`
7. run `php artisan db:seed`
8. lastly, run `php artisan serve` or preferably create a virtual host