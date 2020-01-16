<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## FIRST STEPS


### Step 1

Create image docker with **docker-compose**:

`$ docker-compose build`

### Step 2

Create containers and configurations of docker with **docker-compose**:

`$ docker-compose up -d`


### Step 3

Entry bash container **projectbaselaravel_app_1**:


`$ docker exec -it projectbaselaravel_app_1 bash`


### Step 4

Install dependecies:

Warning: run the commands bellow in container application.

`$ composer install`
