<p align="center">
    <h1 align="center">POS System Using Laravel</h1>
</p>

## Installation

### Requirements
For system requirements you [Check Laravel Requirement](https://laravel.com/docs/9.x/deployment#server-requirements)
#
Laravel utilizes [Composer](https://getcomposer.org/) to manage its dependencies. 

### Conf.example` file to `.env` 1.`php artisan key:generate` to generate app key.

1. Set your database credentials 
1. Set your `APP_URL` in your `.env` 


### Database
1. Migrate database table `php artisan migrate`
1. `php artisan db:seed`, this will initialize settings and create and admin user for you [email: admin@gmail.com  - password: admin123]
### Run Server

1. `php artisan serve` or Laravel Homestead
1. Visit `localhost:8000` in your browser. Email: `admin@gmail.com`, Password: `admin123`.
### Screenshots

#### Product list

![Product list](https://raw.githubusercontent.com/Hamzzyy/LaravelPOS/master/screenshots/products_list.png)

#### Create order

![Create order](https://raw.githubusercontent.com/Hamzzyy/LaravelPOS/master/screenshots/pos.png)

#### Order list

![Order list](https://raw.githubusercontent.com/Hamzzyy/LaravelPOS/master/screenshots/order_list.png)

#### Customer list

![Customer list](https://raw.githubusercontent.com/Hamzzyy/LaravelPOS/master/screenshots/customer_list.png)

