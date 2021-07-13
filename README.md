# Docker Build

Create a docker repository on Docker Hub

### Build image and name it

```
docker build --tag samsungui .
```

### Login to Docker Hub

```
docker login
```

### Tag the image

```
docker tag samsungui {DOCKER_USERNAME}/samsungui:1.0
```

### Push the image to Docker Hub repository

```
docker push {DOCKER_USERNAME}/samsungui:1.0
```

### Verify repository exists with tag

```
https://hub.docker.com/r/drakedev/samsungui/tags
```

# Prometheus Targets

### cAdvisor

```
https://hub.docker.com/r/google/cadvisor
```

### Node Exporter

```
https://hub.docker.com/r/prom/node-exporter
```

### Postgres Exporter

```
https://hub.docker.com/r/wrouesnel/postgres_exporter
```
