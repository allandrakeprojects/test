# Getting Started
### Installation

1. Pull image
   ```
   docker pull drakedev/samsungui:v0.0.1
   ```
2. Run image
   ```
   docker run -d -p 8080:80 --name samsungui drakedev/samsungui:v0.0.1
   ```

# Prerequisites

### Prometheus

```
https://hub.docker.com/r/prom/prometheus
```

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
