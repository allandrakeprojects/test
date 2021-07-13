## Getting Started

### Prerequisites

* Prometheus

```
https://hub.docker.com/r/prom/prometheus
```

* Node Exporter

```
https://hub.docker.com/r/prom/node-exporter
```

* Postgres Exporter

```
https://hub.docker.com/r/wrouesnel/postgres_exporter
```

* cAdvisor

```
https://hub.docker.com/r/google/cadvisor
```

* DCGM

```
https://hub.docker.com/r/nvidia/dcgm-exporter
```

### Installation (temp docker hub repo)

1. Pull image
   ```
   docker pull drakedev/samsungui:v0.0.1
   ```
2. Run image
   ```
   docker run -d -p 8080:80 --name samsungui drakedev/samsungui:v0.0.1
   ```
3. Configuration of data source
