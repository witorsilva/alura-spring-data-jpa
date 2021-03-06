# ALURA SPRING DATA JPA 

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

> EXAMPLE JPA TO SPRING DATA.

<!-- GETTING STARTED -->
## Getting Started

Project created for examples to alura course

### Prerequisites

* JDK 8
* MariaDB
* Docker
  
## Database

### Simple Installation  MariaDB For Docker

* GET TO MARIADB IMAGE
    ```sh
      docker pull mariadb
  ```
  
* CREATE AND RUN CONTAINER TO MARIADB
    ```sh
    docker run -p 127.0.0.1:3306:3306 --name some-mariadb -e MYSQL_ROOT_PASSWORD=mariadb -d mariadb:latest
    ``` 

Spring data will create tables automatically

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
    
## Installation  


  
