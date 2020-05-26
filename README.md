# Composer
## Build
> docker-compose up -d --build

## Up
> docker-compose up

## Down
> docker-compose down

## Create environment file
> cp -p .evn.sample .env

`Update the values of your sandbox`

## Test the app running
http://symfony.localhost

# Symfony create project

## Create project
> cd application

### To build traditional web application
> composer create-project symfony/website-skeleton .

### To build a microservice, console application or API
> composer create-project symfony/skeleton .
