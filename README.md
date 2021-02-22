# twitter
Developing a twitter clone using laravel and Mysql

Steps: (2nd commit explanation)

-> Instalation Via Composer

If your computer already has PHP and Composer installed, you may create a new Laravel project by using Composer directly. After the application has been created, you may start Laravel's local development server using the Artisan CLI's serve command:

composer create-project laravel/laravel example-app

cd example-app

php artisan serve

-> Install breeze for login and register

Once you have created a new Laravel application, you may install Laravel Breeze using Composer:

composer require laravel/breeze --dev
After Composer has installed the Laravel Breeze package, you may run the breeze:install Artisan command. This command publishes the authentication views, routes, controllers, and other resources to your application. Laravel Breeze publishes all of its code to your application so that you have full control and visibility over its features and implementation. After Breeze is installed, you should also compile your assets so that your application's CSS file is available:

php artisan breeze:install

npm install

npm run dev

php artisan migrate

npm install tailwindcss

