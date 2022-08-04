# Docker Basic Commands

> `docker images`
> check all existing images.


> `docker pull <imagename>`
> pull image from docker repository

> `docker run <imagename>`
> Run image in do container
> `docker run -d <imagename>`
> run image in detached mode
> `docker run -p<host>:<containerport>`
> bind specific port
> `docker run -d p-6001:6379 --name <name> <image Name>`
> change image name

> `docker ps`
> list running containers

> `docker stop <container Id>`
> Stop the container

> `docker start <container Id>`
> starts stopped  container

> `docker ps -a`
> List running and stopped container

> `docker logs <container id>`
> get container logs

> `docker exec -it <container id> /bin/bash`
> Enter to the Container terminal

> `docker network create <Net Name>`
> create New Network

> `docker rm <Container Id>`
> Delete docker Container

> `docker rmi <Image Id>`
> Delete docker image