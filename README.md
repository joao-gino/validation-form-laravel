## About project
Just a starter project to show an application that envolves a validation form.

## How to run
### Do the download and with terminal in the directory of the project, run the command below to install all the dependencies
```
composer install
```
### Next, set in your .env the parameters to connect to your database and run.
```
php artisan key:generate
```
#### Your .env need to have this (but with your connections, of course)
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=hackernews
DB_USERNAME=root
DB_PASSWORD=
```
### After this, run the migrations with
```
php artisan migrate
```
### And this to see te project in your browser.
```
php artisan serve
```
