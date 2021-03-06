
[<p align="center"><img  width="300" src="covid19.svg" align="center"/></p>](http://covid19.sabtinam.com)

&nbsp;
# CoronaVirus Tracker

> This is the source code repository for [CoronaVirus Tracker](http://covid19.sabtinam.com). The code is entirely open source and licensed under the [MIT license](LICENSE). Read the installation guide below to get started with setting up the app on your machine.

## ABSTRACT
Find out the place or path between two endpoints which is less infected to the Coronavirus (COVID-19). Through this app, you can explore which places are infected to the coronavirus (COVID-19), find out the base path between two places which is less Infected to the coronavirus (COVID-19) and also you can get the latest information from the World Health Organization about COVID-19.

## Requirements

Before installing the app you will need to make sure your server meets the following requirements:

- PHP >= 7.2.5
- BCMath PHP Extension
- Ctype PHP Extension
- Fileinfo PHP extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

## Installation

1. Clone this repository
2. Run `composer install`
3. Install `node package manager` on your local machine: `https://nodejs.org/en`
4. Run `npm install` to install the dependencies as defined in the package.json file.
5. you can create `.env` by `cp .env.example .env` 
	then add your database credential in it.
6. Run `php artisan key:generate` to generate a key for your app.
7. Run `php artisan migrate --seed` to run the database migrations.
8. Run `php artisan serve` to Serve the application on the PHP development server.

> You can now visit the app in your browser by visiting [http://127.0.0.1:8000](http://127.0.0.1:8000).
