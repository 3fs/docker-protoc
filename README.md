DOCKER-PROTOC
=============

Docker image for converting `.proto` files in any given project.

How to use it
-------------

```
docker run --rm -v $PWD/spec:/tmp protoc -I=/tmp --go_out=plugins=grpc:/tmp /tmp/*.proto
```
