# Spring Boot Camel XML QuickStart

This example demonstrates how to configure Camel routes in Spring Boot via
a Spring XML configuration file.

The application utilizes the Spring [`@ImportResource`](http://docs.spring.io/spring/docs/current/javadoc-api/org/springframework/context/annotation/ImportResource.html) annotation to load a Camel Context definition via a _src/main/resources/spring/camel-context.xml_ file on the classpath.

IMPORTANT: This quickstart can run in one modes: standalone on your machine.

## Running the quickstart standalone on your machine through CLI

To run this quickstart as a standalone project on your local machine:

* Build the project:

    $ mvn clean package
    
* Run the service:

    $ mvn spring-boot:run

* See the messages sent by Camel.
