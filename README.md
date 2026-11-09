# SP500 Connection Service

Spring Boot draft of the connection service for an S&P 500 analytics app.

## Stack

- Java 11+ (tested with JDK 17)
- Spring Boot 2.7, Spring Web, Spring Data MongoDB
- ModelMapper

## Run

    ./mvnw spring-boot:run

## Test

    ./mvnw test

## Status

Draft: the application context and the ModelMapper bean are set up,
there are no endpoints yet. MongoDB connection settings go into
`src/main/resources/application.properties`.
