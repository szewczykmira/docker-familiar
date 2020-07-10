# docker-familiar
My systematised knowledge about docker.

## Instalation
To clone this repository please run this command:
```sh
git clone --recursive git@github.com:szewczykmira/docker-familiar.git
```


## Dictrionary

__Image__ - everything needed to run container - the code/binary, runtimes, dependencies and other objects required.
__Container__ - running process isolated from host and other containers. Every container has its own filesystem.
__Build__ - Build image with proper context

## Image
`docker image ls` list all images


## Container
`docker container ls` / `docker ps` list all containers

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`--all` show all containers as default shows only running containers

`docker container rm` / `docker rm` - remove container(s)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`--force`/`-f` allows to remove running containers

## Build
`docker build` build image from Dockerfile

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `--tag`/`-t` name image with optional tag (name:tag)

## Run
`docker run` - Runs image as a container

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `--publish`/`-p` publish containers traffic to the host (host:container)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `--detach`/`-d` run container in background

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `--name` specify a name for container which you can refer to your container

## Stop
``docker stop <name>` - stopps running container