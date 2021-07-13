## Getting Started
### Installation (temp Docker Hub repo)

1. Pull image
   ```
   docker pull drakedev/samsungui:v0.0.1
   ```
2. Run image
   ```
   docker run -d -p 8080:80 --name samsungui drakedev/samsungui:v0.0.1
   ```

## Prerequisites

### Prometheus

```
https://hub.docker.com/r/prom/prometheus
```

### Node Exporter

```
https://hub.docker.com/r/prom/node-exporter
```

### cAdvisor

```
https://hub.docker.com/r/google/cadvisor
```

### Postgres Exporter

```
https://hub.docker.com/r/wrouesnel/postgres_exporter
```

### DCGM

```
https://hub.docker.com/r/nvidia/dcgm-exporter
```
