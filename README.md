## About The Alura Spring Data Jpa Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Project created for examples JPA SPRING DATA of alura course

<!-- GETTING STARTED -->
## Getting Started

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
    
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/witorsilva/alura-spring-data-jpa.git
   ```
2. Install MAVEN packages
   ```sh
   mvn install
   ```

<!-- MARKDOWN LINKS & IMAGES -->
## LINKS
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
* [JDK8](https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html)
* [DOCKER](https://www.docker.com/)
* [MAVEN](https://maven.apache.org/)
* [MARIADB DOCKER](https://hub.docker.com/_/mariadb)
* [MARIADB](https://mariadb.org/)



[product-screenshot]: https://raw.githubusercontent.com/othneildrew/Best-README-Template/master/images/screenshot.png
