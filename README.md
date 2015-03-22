# abroute_docker_base - base image, shared by abroute_docker images
This is the common portion of the image for the abroute_docker group

## Overview

Share the same base image.  Since each of these scripts is probably run on the same docker platform,
might as well only download the common parts once.

I may put the compositions here are well.

## Docker Container Layout

![alt text][docker_containers]

[docker_containers]:https://github.com/lgfausak/sqlauth/raw/master/docs/docker_containers.png "Docker Containers"
