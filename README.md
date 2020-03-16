# plex

Configuration for dockerized Plex media server

## Requirements

- Docker
- Docker compose

## Running

```
cp .env.example .env
```

Fill in fields in `.env`

```
docker stack deploy -c <(docker-compose config) plex
```
