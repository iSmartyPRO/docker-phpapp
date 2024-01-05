# Docker PHP-FPM 8.x and Nginx

![nginx](https://img.shields.io/badge/nginx-brightgreen.svg)
![php](https://img.shields.io/badge/php-fpm-brightgreen.svg)
 
* Built on the lightweight
* Multi-platform, supporting
* Uses PHP 8.x for better performance, lower CPU and memory usage
* Use only resources when traffic exists

# How it works?

1. Select PHP version by editing file: ```./docker/php-fpm/Dockerfile```
2. Define container name and port by editing file: ```./.env```
3. Run docker container by follwoing command ```docker-compose up -d``` or if you want to shutdown application use following command ```docker-compose down```


### Notes:
* in my projects I'm using common network called **docker_lan** if you dont have common network you have to create it by follwoing command: ```docker network create docker_lan```