# rails-docker-compose

Docker-compose file for rails app with webpack and sideqk

# For Development in docker

## Install docker from [link](https://docs.docker.com/engine/install/) And install docker-compose install from [link](https://docs.docker.com/compose/install/)

### Then run

```
docker-compose build
docker-compose up
```

## To run migrations

```
docker-compose exec web rails db:mirate
```

## To create any migrations

```
docker-compose exec web rails g migration
```

## If u add any gem or add new yarn package run stop docker-compose by CTRL+C and run

```
docker-compose down -v
docker-compose build
docker-compose up
```
