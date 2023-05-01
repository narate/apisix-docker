# APISIX Docker Compose Deployment

## Start all services

```
docker compose up -d
```

## Services Port

| Service | Port |
|---:|---|
| APISIX HTTP Proxy | 80   |
| APISIX HTTPS Proxy| 443  |
| APISIX Admin API  | 8001 |
| APISIX Control API| 9090 |
| APISIX Dashboard  | 9000 |
| Prometheus        | 9091 |


## Dashboard Admin username/password
| Username | Password |
|---:|---|
| admin | admin |

## Admin API Key

| Header Name | Value |
|---:|---|
| X-Api-Key | edd1c9f034335f136f87ad84b625c8f1 |


## Config files

| Service | File Path |
|---:|---|
| APISIX | [conf/apisix-config.yaml](./conf/apisix-config.yaml) |
| APISIX Dashboard| [conf/apisix-dashboard-config.yaml](./conf/apisix-dashboard-config.yaml) |

[Getting started](https://apisix.apache.org/docs/apisix/getting-started/)
