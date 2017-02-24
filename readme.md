Steps of installation
---------------------
1- type in your terminal this command
composer update
to install the node modules

2- you have to generate a key for your application so write in your terminal

php artisan key:generate

3- copy the .env.example file with a new name .env and write your db name and your username and password for mysql

4- to run your migrations write in your terminal 

php artisan migrate

5- your application is ready for running so if you want to run your laravel server write in your terminal

php artisan serve

6- to start your workflow in the application you have to register first
