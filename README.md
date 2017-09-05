#docker-node basic container

This module steps through the basic process for creating a Docker container based on NodeJs. 

## build
```
docker build -f Dockerfile -t markhughes/docker-node .
```

## run
```
docker run -d -p 8080:3000 markhughes/docker-node
```

## push
```
docker push markhughes/docker-node
```

## pull
```
docker pull markhughes/docker-node
```

## Sources

image on DockerHub
[https://hub.docker.com/r/markhughes/docker-node]
(https://hub.docker.com/r/markhughes/docker-node/)

src on github
[https://github.com/markmachine/docker-node]
(https://github.com/markmachine/docker-node)

