---
layout: post
title: Skeleleton Api with Slim PHP
---

## APP:

Skeleton for RESTful API development using [Slim PHP micro framework](http://www.slimframework.com).

Used technologies: PHP, Slim PHP, MySQL, PHPUnit, env var, Docker & Docker Compose.

## QUICK INSTALL:

### Pre Requisite:

- Git.
- Composer.
- PHP.
- MySQL/MariaDB.

### Run commands:

In your terminal execute this commands:

```bash
$ git clone https://github.com/maurobonfietti/skel-api-slim-php.git && cd skel-api-slim-php
$ cp .env.example .env
$ composer install
$ composer test
$ composer start
```


## DOCKER READY:

If you like Docker, you can use this project with **docker** and **docker-compose**.


### MINIMAL DOCKER VERSION:

* Engine: 18.03+
* Compose: 1.21+


### Docker Commands:

```bash
# Create and start containers for the API.
$ docker-compose up -d --build

# Checkout the API.
$ curl http://localhost:8081

# Stop and remove containers.
$ docker-compose down
```


For more info: [view repository](https://github.com/maurobonfietti/skel-api-slim-php).

----
