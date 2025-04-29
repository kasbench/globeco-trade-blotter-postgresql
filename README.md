# globeco-trade-blotter-postgresql
PostgreSQL docker file for the globeco-trade-blotter-microservice


To build:

```
docker build -t kasbench/globeco-trade-blotter-posgresql .
```

To run:

```
docker run -d --name globeco-trade-blotter-postgresql \
  -p 5432:5432 \
  -e POSTGRES_HOST_AUTH_METHOD=trust \
  kasbench/globeco-trade-blotter-posgresql
```


