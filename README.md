# Scaffolding

## MySQL 5.7

### Run

```shell
$ docker-compose --file mysql-5.7.yml up --detach
```

### Connect

```shell
$ docker exec --interactive --tty mysql-5.7 mysql -uroot -p
```

### Tear down

```shell
$ docker-compose --file mysql-5.7.yml down
```
