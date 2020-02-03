<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>


## FIRST STEPS


### Step 1

Create image docker with **docker-compose**:

`$ sudo docker-compose build`

### Step 2

Create containers and configurations of docker with **docker-compose**:

`$ sudo docker-compose up -d`


### Step 3

Entry bash container **projectbaselaravel_app_1**:


`$ docker exec -it projectbaselaravel_app_1 bash`


### Step 4

Install dependecies:

Warning: run the commands bellow in container application.

`$ composer install`
`$ chown -R www-data:www-data storage/`
`$ php artisan migrate`
`$ php artisan db:seed`
