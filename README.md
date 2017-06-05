# Java, Maven with Python and Node env to run tests

Base image from: joaovitor/python-gcloud-node:v4
 - openjdk-7 - 7u131
 - maven - 3.5.0

# Docker hub

[joaovitor/python-gcloud-java](https://hub.docker.com/r/joaovitor/python-gcloud-java/)

# Commands

## Build the image
```
docker build -t joaovitor/python-gcloud-java:v1 .
```

## Push the image

```
docker push joaovitor/python-gcloud-java
```
