# plex

Configuration for dockerized Plex media server

## Requirements

- Docker
- Docker compose

## Running

### Environment variables

```
cp .env.example .env
```

Fill in fields in `.env`

### Run in docker swarm mode

```
docker stack deploy -c <(docker-compose -f docker-compose.yml -f docker-compose.swarm.yml config) plex
```

### Run in docker compose mode

```
docker-compose up -d
```
