## [ubuntu-armhf-tomcat](https://github.com/pelayolluna/docker-hub/tree/master/repositories/ubuntu-armhf-tomcat)
[![Hex.pm](https://images.microbadger.com/badges/version/lluna89/ubuntu-armhf-tomcat.svg)](https://microbadger.com/images/lluna89/ubuntu-armhf-tomcat) [![Hex.pm](https://images.microbadger.com/badges/image/lluna89/ubuntu-armhf-tomcat.svg)](https://microbadger.com/images/lluna89/ubuntu-armhf-tomcat) [![Hex.pm](https://img.shields.io/docker/stars/lluna89/ubuntu-armhf-tomcat.svg)](https://hub.docker.com/r/lluna89/ubuntu-armhf-tomcat/) [![Hex.pm](https://img.shields.io/docker/pulls/lluna89/ubuntu-armhf-tomcat.svg)](https://hub.docker.com/r/lluna89/ubuntu-armhf-tomcat/)

### Description
- Distribution: Ubuntu
- Architecture: armhf
- Base Image: armv7/armhf-java8
- Application: Tomcat (Apache Tomcat is an open-source Java Servlet Container developed by the Apache Software Foundation (ASF), Tomcat implements several Java EE specifications including Java Servlet, JavaServer Pages (JSP), Java EL, and WebSocket, and provides a "pure Java" HTTP web server environment in which Java code can run)

### Pull
`docker pull lluna89/ubuntu-armhf-tomcat`

### Run
`docker run -it -p 8080:8080/tcp lluna89/ubuntu-armhf-tomcat`

### Usage
- URL: http://localhost:8080/

### Ports
| Port  | Description |
| ------------- | ------------- |
| 8080/tcp  | HTTP port  |
