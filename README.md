# Laravel in Docker

##### 🔥 Laravel in Docker. Starter Kit 🚀

### Start

Start Laravel in Docker

```shell
cp .env.example .env
docker-compose up --build -d
```

### Commands

- Start command

```shell
docker-compose up --build -d
```

- Stop all containers

```shell
docker stop $(docker ps -a -q)
```

- Delete all stoped images

```shell
docker system prune --all --force --volumes
```

- Enter to container

> if /bin/sh

```shell
docker exec -it `container_name` /bin/sh;
```
