# CRUD-GO

- Run project
```
go run main.go
```

- Run postgres - docker
if runner in background include -d

```
docker-compose -f pg.yaml up  
```

- Stop postgres - docker
this command stop docker, referrer container in pg.yaml

```
docker-compose -f pg.yaml stop  
```

- Down postgres - docker
this command down docker, referrer container in pg.yaml
he remove containers referrer in pg.yaml
```
docker-compose -f pg.yaml down  
```