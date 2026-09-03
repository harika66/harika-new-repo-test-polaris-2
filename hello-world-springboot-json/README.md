
# hello-world-springboot-json

A minimal Spring Boot (3.x) project using Maven that returns a JSON response.

## Requirements
- Java 17+
- Maven 3.8+

## Run
```bash
mvn clean package
mvn spring-boot:run
# or
java -jar target/hello-world-springboot-json-0.0.1-SNAPSHOT.jar
```

Visit:
- http://localhost:8080/hello -> `{ "message": "Hello, World!" }`
- Health: http://localhost:8080/actuator/health

## Test
```bash
mvn test
```
