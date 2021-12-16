# ecmascript-modules-test

## Summary

- [Requirements](#requirements)
- [Optional requirements](#optional-requirements)
- [Usage](#usage)
  - [Start](#start)
    - [Makefile](#makefile)
    - [Docker Compose](#docker-compose)
  - [Stop](#stop)
    - [Makefile](#makefile-1)
    - [Docker Compose](#docker-compose-1)
  - [Restart](#restart)
    - [Makefile](#makefile-2)
    - [Docker Compose](#docker-compose-2)
- [Endpoints](#endpoints)

## Summary

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
