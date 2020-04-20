# Scaffolding

## MySQL 5.7

### Set up

Create a `.env.mysql` file in the `mysql-5.7` directory with the following contents:

```shell
MYSQL_ROOT_PASSWORD=<password>
```

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

### Set up

Create a `.env.postgresql` file in the `postgres-9.6` directory with the following contents:

```shell
POSTGRES_PASSWORD=<password>
```

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
