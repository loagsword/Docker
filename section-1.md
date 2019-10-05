### Test Docker Version
1. use `docker --version` to check docker version.

2. Run `docker info` to see more details about the docker installation.

### Test Docker Installation
1. Test Docker Installation with `docker run hello-world`.

2. list the `hello-world` image that was pulled to your machine using `docker image ls`.

3. `docker container ls --all` will list the `hello-world` containers spawned by the image and existing after displaying its image.

### Recap

```
## List Docker CLI commands
docker
docker container --help

## Display Docker version and info
docker --version
docker version
docker info

## Execute Docker image
docker run hello-world

## List Docker images
docker image ls

## List Docker containers (running, all, all in quiet mode)
docker container ls
docker container ls --all
docker container ls -aq
```

