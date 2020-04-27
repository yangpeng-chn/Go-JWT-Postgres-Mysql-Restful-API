# Run mysql and golang api with containers

### How to run

```bash
docker-compose up --build 
```

### Access

API: [http://localhost:8080/](http://localhost:8080/)

Mysqladmin: [http://localhost:9090/](http://localhost:9090/)

### Stop

```bash
docker-compose down --remove-orphans --volumes
```