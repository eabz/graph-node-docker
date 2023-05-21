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

## Nginx configuration

There is an optional configuration file to add an nginx proxy to use with a domain.

## Contribution Guidelines

Developers are expected to follow contribution guidelines to keep the codebase efficient, readable, and standardized. Contribution guidelines are clearly laid out so developers and contributors can submit their work without much revision, resulting in faster development and more useful contributions. These guideliness are specified through the `rome` configuration.