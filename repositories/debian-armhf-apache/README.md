# [debian-armhf-apache](https://hub.docker.com/r/lluna89/debian-armhf-apache/)
[![Hex.pm](https://images.microbadger.com/badges/version/lluna89/debian-armhf-apache.svg)](https://microbadger.com/images/lluna89/debian-armhf-apache) [![Hex.pm](https://images.microbadger.com/badges/image/lluna89/debian-armhf-apache.svg)](https://microbadger.com/images/lluna89/debian-armhf-apache) [![Hex.pm](https://img.shields.io/docker/stars/lluna89/debian-armhf-apache.svg)](https://hub.docker.com/r/lluna89/debian-armhf-apache/) [![Hex.pm](https://img.shields.io/docker/pulls/lluna89/debian-armhf-apache.svg)](https://hub.docker.com/r/lluna89/debian-armhf-apache/)

##Description
- Distribution: Debian
- Architecture: armhf
- Base Image: armv7/armhf-debian
- Application: Apache (Apache HTTP Server is the world's most used web server software. Apache is developed and maintained by an open community of developers under the auspices of the Apache Software Foundation)

##Pull
docker pull lluna89/debian-armhf-apache

##Run
docker run -it -p 80:80/tcp -p 443:443/tcp lluna89/debian-armhf-apache

##Usage
- URL: http://localhost:80/

##Ports
| Port  | Description |
| ------------- | ------------- |
| 80/tcp  | HTTP port  |
| 443/tcp  | HTTPS port  |
