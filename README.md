# docker-compose elasticsearch oss

Docker-compose stack with [elasticsearch](https://www.elastic.co/) oss and kibana oss

## Requirements

- [docker-compose](https://docs.docker.com/compose/)

## Usages

Elastic and Kibana versions are driven by the [.env](.env) file.

```sh
docker-compose up -d
```

```sh
docker-compose logs -f
```

```sh
docker-compose logs -f elasticsearch
```