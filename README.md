# Spring Boot Restful Web Services Example

Guide

This is a part of the tutorial http://javabycode.com/spring-framework-tutorial/spring-boot-tutorial/spring-boot-restful-web-services-example.html

What you'll need

    JDK 1.8 or later
    Maven 3 or later
    spring-boot 1.4.3.RELEASE


Run

    mvn clean install
    mvn spring-boot:run
    
To call the get endpoint to bit coin data:

http://localhost:8081/bitcoin


To run docker: 
mvn clean install
docker build -t spring-server .
docker run -p 5000:8081 spring-server:latest

The app should be deployed on port 5000

Follow instructions for docker setup on the website:
https://www.callicoder.com/spring-boot-docker-example/