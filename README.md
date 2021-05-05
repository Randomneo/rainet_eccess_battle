# Rainet access battle

Web implementation of Stains;Gate board/card game.

# Installation

1. Pull repo

2. Build docker images

    docker-compose build

3. Add .env file to contain following values:

    BE_INNER_UVICORN_PORT=8080
    RUNNING_MODE=DEVELOPMENT/SANDBOX/PRODUCTION

4. Run web service

    docker-compose up

5. Run backend tests with

    docker-compose exec backend pytest


By default server will start in development mode on localhost

To change mode edit .env file. Example is added by dev-env, prod-env (those files will require editing).

# Game rules/description:

## TODO

# Demo (Work in progress): [demo](https://randomneo.dev/rainet-access-battle/)
