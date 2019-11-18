# Fitness Buddy
A social platform where fit and fitness enthusiast meet

## Installation Tools Required
- Docker
- Maven
- Java 1.8

## Run build and test
``mvn clean install``

## Build docker environment
- Prepare mvn docker dependency build ``./mvnw install dockerfile:build``
- Build container and start ``docker-compose up --build``
- Start container ``docker-compose start``
- Stop container ``docker-compose stop ``

**_notice: if you got the error like: `Connect to localhost:2375 [localhost/127.0.0.1, localhost/0:0:0:0:0:0:0:1] failed: Connection refused` [please see this](https://github.com/spotify/docker-maven-plugin/issues/355#issuecomment-406713023)_**

## Swagger Documentation
http://localhost:8080/swagger-ui.html

## Health
http://localhost:8080/actuator/health
