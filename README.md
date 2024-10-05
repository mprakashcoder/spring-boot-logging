# spring-boot-logging demo


## 1)Default Logging Setup
By default, Spring Boot:

<ul><li>Uses Logback as the underlying logging framework.</li><br>
<li>Logs output to the console.</li><br>
<li>Supports logging levels: TRACE, DEBUG, INFO, WARN, ERROR, and FATAL.</li></ul>

 ### Technical Details
In this project, we are going to use below set of versions for demonstrations.

    Spring Boot - 3.3.3
    Spring - 6.1.12
    Lombok - 1.18.34
    jdk-17

### Building

The example can be built with
```shell
mvn clean install
```

### Running the example in your local
```shell
mvn clean spring-boot:run
```
