### How to use this spring-boot project

- Install packages with `mvn package`
- Run `mvn spring-boot:run` for starting the application (or use your IDE)

Application (with the embedded H2 database) is ready to be used ! You can access the url below for testing it :

- Swagger UI : http://localhost:8080/swagger-ui.html
- H2 UI : http://localhost:8080/h2-console

> Don't forget to set the `JDBC URL` value as `jdbc:h2:mem:testdb` for H2 UI.



### Instructions

- download the zip file of this project
- create a repository in your own github named 'java-challenge'
- clone your repository in a folder on your machine
- extract the zip file in this folder
- commit and push

- Enhance the code in any ways you can see, you are free! Some possibilities:
  - Add tests
  - Change syntax
  - Protect controller end points
  - Add caching logic for database calls
  - Improve doc and comments
  - Fix any bug you might find
- Edit readme.md and add any comments. It can be about what you did, what you would have done if you had more time, etc.
- Send us the link of your repository.

#### Restrictions
- use java 8


#### What we will look for
- Readability of your code
- Documentation
- Comments in your code 
- Appropriate usage of spring boot
- Appropriate usage of packages
- Is the application running as expected
- No performance issues

### Features: Employee CRUD Service

- Rest Controller for Employee Service.
- Employee service class and its implementation.
- Spring security to protect rest endpoints.
- Caching layer for enabling caching for this Service using Hazelcast configuration.
- Swagger configuration for API documentation.
- WebMVC configuration and Interceptors to enable CorrelationId injection in each request.
- Custom exception handlers and API responses and Util classes.
- Actuator framework support for Application health check.
- Logging using Sl4j framework.
- JUnits support for implementation and business logic.
- Profile based configuration file.
----------------------------------------------------------------------------
----------------------------------------------------------------------------

### Further Enhancement/Scope
 - UML/Sequence Diagram for endpoints Design flow.
 - Actuator framework customization.
 - Monitoring framework (Grafana, Jennifer).
 - CI/CD.
 - Integration testing.
 - UI integration.
 - Spring config server.
 - Containerization(Docker/K8s).
 - SonarQube/SonarLint integration for code coverage/code optimization.
 - Flight Recorder to collect data by continuously monitoring the JVM and recording events into a circular buffer.
 - JMeter for load testing, functional testing, and performance testing.
----------------------------------------------------------------------------
----------------------------------------------------------------------------

### About Myself
Hi! This is Sajib. I have been working with Java + Spring Framework over 4 years now. Although I have some built Data 
analytics platforms with Python + Django Framework, but most of my professional experiences on building backend 
microservices with Java and Spring Tech stack. 

