# Scaffolding

## MySQL 5.7

### Run

```shell
$ cd scaffolding/mysql-5.7
$ docker-compose up --detach
```

### Connect

```shell
$ docker exec --interactive --tty mysql-5.7 mysql -uroot -p
```

### Tear down

```shell
$ docker-compose down
```

## PostgreSQL 9.6

### Run

```shell
$ cd scaffolding/postgres-9.6
$ docker-compose up --detach
```

### Connect

```shell
$ docker exec --interactive --tty postgres-9.6 psql --user postgres
```

### Tear down

```shell
$ docker-compose down
```
