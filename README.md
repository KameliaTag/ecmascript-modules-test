# ecmascript-modules-test

## Requirements

- Docker
- Docker Compose

## Optional requirements

- GNU/Make

## Usage

### Start

```bash
make start # makefile
docker-compose up --detach # docker-compose
```

### Stop

```bash
make stop # makefile
docker-compose down --remove-orphans --volumes --timeout 0 # docker-compose
```

### Restart

```bash
make restart # makefile
docker-compose down --remove-orphans --volumes --timeout 0 && docker-compose up --detach # docker-compose
```

## Endpoints

URL | Description
---|---
[`localhost:8080`](http://localhost:8080) | Webserver root
