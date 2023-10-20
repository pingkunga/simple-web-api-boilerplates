# HOW TO RUN?

1. cd path_to_your_project
2. ```bash
   mvn clean install
   ```
3. ```bash
   java -jar target/demo-0.0.1-SNAPSHOT.jar
   ```

# HOW TO TEST

```
curl http://localhost:8080/greeting
```

or

```bash
curl http://localhost:8080/greeting?name=John
```
