# [ubuntu-armhf-nginx](https://hub.docker.com/r/lluna89/ubuntu-armhf-nginx/) [![Hex.pm](https://images.microbadger.com/badges/version/lluna89/ubuntu-armhf-nginx.svg)](https://microbadger.com/images/lluna89/ubuntu-armhf-nginx) [![Hex.pm](https://images.microbadger.com/badges/image/lluna89/ubuntu-armhf-nginx.svg)](https://microbadger.com/images/lluna89/ubuntu-armhf-nginx) [![Hex.pm](https://img.shields.io/docker/stars/lluna89/ubuntu-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/ubuntu-armhf-nginx/) [![Hex.pm](https://img.shields.io/docker/pulls/lluna89/ubuntu-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/ubuntu-armhf-nginx/)

##Description
- Distribution: Ubuntu
- Architecture: armhf
- Base Image: armv7/armhf-ubuntu
- Application: Nginx (Nginx is a web server, which can also be used as a reverse proxy, load balancer and HTTP cache. Nginx was created by Igor Sysoev)

##Pull
docker pull lluna89/ubuntu-armhf-nginx

##Run
docker run -d -p 80:80/tcp -p 443:443/tcp lluna89/ubuntu-armhf-nginx

##Usage
- URL: http://localhost:80/

##Ports
| Port  | Description |
| ------------- | ------------- |
| 80/tcp  | HTTP port  |
| 443/tcp  | HTTPS port  |
