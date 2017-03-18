# Docker ahoi! - Round 1

Hinweise:

- jede Zeile im Dockerfile erzeugt einen Layer
- statische DInge möglichst nach oben im File

## Goals

* Write your own Dockerfile
* Learn basic Docker Commands

## Help

* [Docs](https://docs.docker.com)
* [Docs > Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [Docs > Commandline](https://docs.docker.com/engine/reference/commandline/cli)

## Tasks - Round 1

### Write your first Dockerfile

Fill out `Dockerfile`

### Build docker image

docker build -t round-1 .
___

### Run docker container

docker container run -p 127.0.0.1:5000:1337 9c59fff26a92
___

### List running docker containers

docker ps
___

### Stop docker container

docker container stop XYZ
___

### List all docker containers

docker ps -a
___

### Remove created container

 docker image rm xyz
___

### Run docker container with removal

docker container run --rm -p 127.0.0.1:5000:1337 xyz
___

### Run docker container in background

docker container run -d -p 127.0.0.1:5000:1337 yxz
___

### Step into container

führt einen Befehl `sh` im container aus

docker exec -it xyz sh
___

### Stop container

___

### Start container

___

### Run docker container and step into

___

### Run docker container with mounted volume

___
