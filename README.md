# ecmascript-modules-test

## Requirements

- Docker
- Docker Compose

## Optional requirements

- GNU/Make

## Usage

### Start

#### Makefile

```bash
make start
```

#### Docker Compose

```bash
docker-compose up --detach
```

### Stop

#### Makefile

```bash
make stop
```

#### Docker Compose

```bash
docker-compose down --remove-orphans --volumes --timeout 0
```

### Restart

#### Makefile

```bash
make restart
```

#### Docker Compose

```bash
docker-compose down --remove-orphans --volumes --timeout 0 && docker-compose up --detach
```

## Endpoints

URL | Description
---|---
[`localhost:8080`](http://localhost:8080) | Webserver root
