# Quiz App

## Overview

This quiz app allows users to participate in quizzes, view their results, and compete on leaderboards.

## Features

#### Admin Features

-   Manage other admins
-   Manage quizzes
-   Manage questions and options
-   View all the tests taken on the system

#### User Features

-   Log in and register
-   Participate in quizzes as a guest or registered user
-   View a specific quiz's results and leaderboard
-   View the overall leaderboard, which ranks all users based on their test results

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

#### Prerequisites

-   Composer dependency manager
-   PHP 8+
-   Laravel 10.18+
-   Livewire 3

#### Installation

1- Clone the project

```
git clone https://github.com/rsrodhia/quiz-app.git
```

2- Install the dependencies

```
composer install
```

3- Configure the environment:

```
cp .env.example .env
```

4- Generate the application key:

```
php artisan key:generate
```

5- Migrate the database:

```
php artisan migrate --seed
```

6- Configure Livewire:

```
php artisan livewire:publish --config
```
```
php artisan livewire:publish --assets
```
configure the "asset_url" in config/livewire.php to customize what's prepended to the src="" attribute
i.e 'asset_url' => '/quiz-app/public'
```
npm install
```

7- Start the development server:

```
npm run dev
```

## Running Tests

To run tests, run the following command

```
  php artisan test
```

## Author

-   [@rsrodhia](https://www.github.com/rsrodhia)
