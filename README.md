# Run this project

Here my first play arounds to play around with docker compose. If you have any questions just ask but basically it's meant for playing around myself.

## Build and run docker compose

  docker-compose build
  docker-compose up

## Check and modify running containers

  docker-compose ps
  docker-compose exec proxy sh
  docker-compose scale app=5