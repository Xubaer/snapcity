# Snap City
This is a photo sharing social media web application.<br>
Visit [DEMO](http://quiet-waters-12647.herokuapp.com)

## Technology Stack
- PHP 7.1
- Node js
- Mysql/Sqlite
- Laravel (5.8)
- Vue js

## Features
- User Authentication and Authorization
- User Feed based on profiles followed
- Create post with caption
- Follow profiles

## Setup Project
```PHP
git clone https://github.com/Xubaer/snapcity.git
cd snapcity
composer install
```
If you sure all packages was downloaded then you have to configure this project. At first create a database and put your database credentials in .env file. .env is local environment file for laravel. After saving this configuration you have to database migrate. To migrate database run this command in your terminal
```PHP
php artisan migrate

npm install ( for vue )
npm run dev

php artisan serve
```

## Features Coming next
- Posts Likes & comments feature
- user notification on profile follow and post like & comment
- user chat system