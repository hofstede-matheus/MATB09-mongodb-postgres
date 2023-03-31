# MATB09-mongodb-postgres

## Inicializar

### Inicializar PostgreSQL e MongoDB

```
docker compose up
```

### Inicializar PostgreSQL

```
docker compose up postgres
```

### Inicializar MongoDB

```
docker compose up mongo
```

## Credenciais

### PostgrSQL

```
POSTGRES_USER=matb09
POSTGRES_PASSWORD=matb09
POSTGRES_DB=matb09_db
```

### MongoDB

```
MONGO_INITDB_ROOT_USERNAME: matb09
MONGO_INITDB_ROOT_PASSWORD: matb09
```

## Finalizar

### Finalizar sem remover volumes

```
docker compose down
```

### Finalizar removendo volumes

```
docker compose down -v
```

https://docs.docker.com/compose/reference/
https://docs.docker.com/engine/reference/commandline/cli/
