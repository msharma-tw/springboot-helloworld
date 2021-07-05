# SPRING BOOT SAMPLE PROJECT
Sample Repository for Spring Boot application with MVC Implementation.

### Run Tests
```
mvn clean test
```

### Build Application
```
mvn package
```

### Run Application
```
java -jar springboot-helloworld-0.0.1-SNAPSHOT.jar
./mvnw spring-boot:run
```

### Browse Application
```
http://localhost:8080
```

### Docker Commands
```
docker build -t springio/gs-spring-boot-docker .
docker run -p 8080:8080 -t springio/gs-spring-boot-docker
```

*** if 8080 is already in use ***
```
docker container ls
docker rm -f <container-name>
```

---------------------------------------------------------------------

# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.5.2/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.5.2/maven-plugin/reference/html/#build-image)
* [Thymeleaf](https://docs.spring.io/spring-boot/docs/2.5.2/reference/htmlsingle/#boot-features-spring-mvc-template-engines)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/2.5.2/reference/htmlsingle/#using-boot-devtools)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.5.2/reference/htmlsingle/#boot-features-developing-web-applications)

### Guides

The following guides illustrate how to use some features concretely:

* [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/)
* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

Referred Resources:
https://www.youtube.com/watch?v=HTuE0GZtnM4
https://spring.io/guides/gs/spring-boot-docker/




