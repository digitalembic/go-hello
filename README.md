# go-hello

The code in this repo is based on an article found here https://www.bogotobogo.com/GoLang/GoLang_Web_Building_Docker_Image_and_Deploy_to_Kubernetes.php

The goal is to build a simple golang app, and build a docker container to run it.

## Dist

Docker image available via dockerhub [here](https://hub.docker.com/r/digitalembic/go-hello).

`docker pull digitalembic/go-hello`

## Build App

Clone this repo, and build. Requires golang.

```bash
go build -o main .
```

## Build Image

Clone this repo, and build. Requires docker.

```bash
docker build -t go-hello .
```

