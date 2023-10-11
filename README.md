# Graph Node Docker

Configuration files to run a The Graph Node using Docker Compose

## Getting Started

First of all, install the dependencies to run this app:

- [Docker](https://www.docker.com/)

```bash
# Clone this repository
$ git clone https://github.com/eabz/graph-node-docker && cd graph-node-docker

# Copy the env file and change the variables
$ cp .env.example .env

# Run the graph node
$ docker-compose up
```

## NGINX configuration

There is an optional configuration file to add an nginx proxy to use with a domain.
