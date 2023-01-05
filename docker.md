# Useful docker commands

## Docker

```bash
docker run
```
```bash
docker exec -it $container_id
```

```bash
docker stop $container_id
```

```bash
docker-compose -f docker-compose-file.yaml up
```

```bash
docker-compose -f docker-compose-file.yaml down
```

```bash
docker pull
```

```bash
docker run
```

```bash
docker ps
```

```bash
docker run --options
```

```bash
docker stop
```

```bash
docker start
```

```bash
docker logs
```

```bash
docker exec -it
```

```bash
docker exec -it [container_name] bin/bash
```

```bash
docker-compose up -d
```

## Docker compose

### Stops containers and removes them 

```bash
docker compose down
```
### Stops containers and removes them 

```bash
docker compose stop
```



psql "dbname=bonus host=postgresql-prod1-throne-entertainment-prod.aivencloud.com user=avnadmin password=iyyswoiw2bj
coj3i port=23131 sslmode=require"


psql “postgresql://postgre_dev_account:qwerty@localhost:5432/dev_bonus” < pd_dump_outbox.sql


psql "postgresql://avnadmin:iyyswoiw2bjcoj3i@postgresql-prod1-throne-entertainment-prod.aivencloud.com:23131/bonus" < pd_dump_outbox.sql
