# Running defaults services

## Create a external network
```
docker network create -d bridge default-svc-network
``` 

## Running compose files

- Running General Compose
```shell
# Running file per file
$ docker-compose up -d
```

- Running NoSQL Compose
```shell
# Running file per file
$ docker-compose -f docker-compose-nosql.yml up -d
```

- Running SQL Compose
```shell
# Running file per file
$ docker-compose -f docker-compose-sql.yml up -d
```