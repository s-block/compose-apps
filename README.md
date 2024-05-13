Development apps tro e run with docker compose

Run docker compose up with services you want to run. 
```shell script
docker-compose up <service> <service> <service> ...
```

For example kafka, zookeeper
```shell script
docker-compose up kafka zookeeper
```

For example redis, postgres
```shell script
docker-compose up redis postgres
```