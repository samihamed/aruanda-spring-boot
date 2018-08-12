# How to run

run

```bash
mvn spring-boot:run
```

```bash
curl http://localhost:8080/
```

```bash
curl -H "Content-Type: application/json" -X POST -d '{
    "firstName": "Sami",
    "lastName": "Hamed"
}'  http://localhost:8080/
```


```bash
curl -X DELETE http://localhost:8080/1
```

```bash
curl -H "Content-Type: application/json" -X PUT -d '{
    "id": 6,
    "firstName": "Samedi",
    "lastName": "Hamedi"
}'  http://localhost:8080/6
```
