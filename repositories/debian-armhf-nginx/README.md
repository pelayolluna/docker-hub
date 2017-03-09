# [debian-armhf-nginx](https://hub.docker.com/r/lluna89/debian-armhf-nginx/)
[![Hex.pm](https://images.microbadger.com/badges/version/lluna89/debian-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/debian-armhf-nginx/)
[![Hex.pm](https://images.microbadger.com/badges/image/lluna89/debian-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/debian-armhf-nginx/)
[![Hex.pm](https://images.microbadger.com/badges/stars/lluna89/debian-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/debian-armhf-nginx/)
[![Hex.pm](https://images.microbadger.com/badges/pulls/lluna89/debian-armhf-nginx.svg)](https://hub.docker.com/r/lluna89/debian-armhf-nginx/)

##Description
- Distribution: Debian
- Architecture: armhf
- Base Image: armv7/armhf-debian
- Application: Nginx (Nginx is a web server, which can also be used as a reverse proxy, load balancer and HTTP cache. Nginx was created by Igor Sysoev)

##Docker Pull Command
docker pull lluna89/debian-armhf-nginx

##Run
docker run -d -p 80:80/tcp -p 443:443/tcp lluna89/debian-armhf-nginx

##Usage
- URL: http://localhost:80/

##Ports
| Port  | Description |
| ------------- | ------------- |
| 80/tcp  | HTTP port  |
| 443/tcp  | HTTPS port  |
