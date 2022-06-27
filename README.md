# SSH-dockerfile

This Dockerfile creates an ssh service inside a docker container


![Docker](https://github.com/s1ntaxe770r/SSH-dockerfile/workflows/Docker/badge.svg)

* default user and password is test



## Building the image


` docker build -t IMAGE_NAME . ` 

## Runing the image 

` docker run -p 22:22 IMAGE_NAME `


## Or simply pull the image 

`docker pull ghcr.io/s1ntaxe770r/image:latest`
