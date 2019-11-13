# Development area

## Requirements:
* OpenJDK 11 or greater
* Maven 3.6 or greater
* Docker version 18.03.1-ce

## Installing dependencies
* Run: `mvn dependency:resolve`

## How to run it during development:
* Run: `mvn spring-boot:run`

## How to build and package this:
* Run: `mvn package`

## How to test
* Run: `mvn test`

## How to get the coverage
* Run: `mvn jacoco:report`

## How to run sonar
* Run: `mvn sonar:sonar`

## How to build and push the docker image
* For building the docker image: `mvn docker:build`
* For pushing the docker image: `mvn docker:push`

**Note**: before run sonar, you need to have Sonarqube installed in your environment or configure a remote Sonarqube in the project properties.

## Environment variables

Before running the application some variables must be to defined

* **DOCKER_USER**: username used in the connect with the docker repository.
* **DOCKER_PASSWORD**: password for the user used in the connection with the docker repository.
* **DOCKER_REPOSITORY**: docker repository name.

### Some Dev references:

* [Spring Data JPA](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
* [Spring Data REST](https://docs.spring.io/spring-data/rest/docs/current/reference/html/)
* [Spring Boot Reference Guide](https://docs.spring.io/spring-boot/docs/current/reference/html/)
* [Structuring Your Code](https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-structuring-your-code.html)
* [Java Bean Validation Basics](https://www.baeldung.com/javax-validation)
