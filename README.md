# Containerized
An app to be deployed either in a Windows container or a Linux container

Images can be found on Docker Hub at https://hub.docker.com/repository/docker/tezizzm/demoapp

Run the images with the following commands respectively:

``` shell
docker run --rm -it -p 8000:80 tezizzm/demoapp:windows2019ns
```

``` shell
docker run --rm -it -p 8000:80 tezizzm/demoapp:ubuntu
```

Navigate to the application at localhost:8000
