# Verdaccio with Docker and Local Storage

This is a local instance of [Verdaccio](https://verdaccio.org) running in a Docker container using Docker Compose.

Simply run `docker-compose up` from this directory to start the local instance (the default port is `4873`).

## Prerequisites

You need to have [Docker](https://www.docker.com/get-started) installed and running on your machine.

## Configuration

The Verdaccio configuration file is located at `conf/config.yaml`. Follow the [configuration documentation](https://verdaccio.org/docs/configuration) to customize it.

To being able to login into the Web UI, you need to add a NPM user:

```sh
npm adduser --registry http://localhost:4873
```
