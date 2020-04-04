# HelloWorld PHP MSQL Containerize

This is example code how to use docker compose to develop the containerise application and how container can easily communicate each other. 

In the example I have used 

- PHP
- MYSQL 

Note:
    These two will be in two different containers and docker-compose file having configuration how they will communicate. Once you start up containers its fetch the latest images and run the container. 
    In the docker-compose file there is mentioned website depends on database means it first create database container than will create website container. 
