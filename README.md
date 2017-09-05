# docker-node basic container

This module steps through the basic process for creating a Docker container based on NodeJs. 

* [build](#build)
* [run](#run)
* [push](#push)
* [pull](#pull)

## build
```console
docker build -f Dockerfile -t markhughes/docker-node .
```

## run
```console
docker run -d -p 8080:3000 markhughes/docker-node
```

## push
```console
docker push markhughes/docker-node
```

## pull
```console
docker pull markhughes/docker-node
```

## Sources

image on [dockerhub](https://hub.docker.com/r/markhughes/docker-node/)

src on [github](https://github.com/markmachine/docker-node)

