# ALURA SPRING DATA JPA 

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

> EXAMPLE JPA TO SPRING DATA.

### Requires

- JDK 8
- MariaDB
- Docker

## Installation

### Simple Installation  MariaDB For Docker

* GET TO MARIADB IMAGE
    ```sh
      docker pull mariadb
  ```
  
* CREATE AND RUN CONTAINER TO MARIADB
    ```sh
    docker run -p 127.0.0.1:3306:3306 --name some-mariadb -e MYSQL_ROOT_PASSWORD=mariadb -d mariadb:latest
    ```
    
## Database

Spring data will created auto tables

* CREATE DATABASE NAME

   ```sh
     alura-spring-data-jpa
    ```
* CREATE NAME USER FOR DATABASE 

   ```sh
    root
    ```
* CREATE PASSWORD FOR USER IN DATABASE

   ```sh
    mariadb
    ```
  
