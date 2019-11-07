# commerceToolsDemo

This is a dockerized version of the commerceTools demo project.

## Prerequisites

- [Docker](https://www.docker.com/)
- [docker-compose v3](https://docs.docker.com/compose/)

## Usage

```
git clone git@github.com:StarHack/commerceToolsDemo.git
cd commerceToolsDemo/
docker-compose up
```

This will create a container based on `openjdk:8` and spawn the `commerceToolsDemo` on [http://localhost:9000/](http://localhost:9000/)