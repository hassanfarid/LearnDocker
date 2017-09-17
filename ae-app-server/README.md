# Afiniti Explorer Docker Image

## Description
The environment is setup for AE server side application. The image is based on CentOS 7.2.

## Tags
 - 0.4 - build on top of 0.3, and installed cmake3 using epel repository
 - 0.3 - build on top of 0.2, and installed sshd
 - 0.2 - build on top of 0.1, and installed gcc5, boost, mysqlcppconn
 - 0.1 - Basic CentOS image with development tools

## Install
The image is hosted on docker hub public repository:
[https://hub.docker.com/r/hassanfarid/ae-app-server](https://hub.docker.com/r/hassanfarid/ae-app-server)

Following command will pull and run container:
```sh
$ docker run -it hassanfarid/ae-app-server
```

## Author
 - Hassan Farid