# Docker Compose DEV

This is a docker compose configuration containing common development tools, mainly databases.

## Run

``` bash
docker-compose up -d
docker-compose down
```

## Reset persistent data

``` bash
rm -rf ./volumes
```