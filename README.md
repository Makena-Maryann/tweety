# Tweety

#### By **Maryann Makena**

## Description

This is a clone of Twitter made with Laravel.

## Setup/Installation Requirements

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/7.x#installation)

Clone the repository

    git clone https://github.com/Makena-Maryann/tweety.git

Switch to the repo folder

    cd tweety

Install all the dependencies using composer

    composer install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

**TL;DR command list**

    git clone git@github.com:gothinkster/laravel-realworld-example-app.git
    cd laravel-realworld-example-app
    composer install
    cp .env.example .env
    php artisan migrate
    php artisan serve

## Features

-   A user can post tweets.
-   A user can follow and unfollow another user.
-   A user can view the tweets of the people they are following on their timeline.
-   A user can view and update their profile.
-   A user can like/dislike tweets.

## License

The Tweety Project is open-sourced licensed under the [MIT license](https://opensource.org/licenses/MIT).

Copyright (c) 2021 **Maryann Makena**
