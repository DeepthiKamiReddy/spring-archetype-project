# spring-archetype-project
This repository contains my Day-1 Spring Framework archetype project. It’s a starter setup created using the Spring/Maven archetype and I’m using it to understand the basic structure, configuration, and flow of a Spring MVC application.


**Spring Framework – Archetype Project**

This project is a basic Spring MVC application generated using a standard Maven archetype. It serves as a starter template to understand the core structure of a Spring application, including controllers, views, configuration files, and the Dispatcher Servlet setup.

Project Purpose

This project was created as part of Spring Framework training to learn:

The default project structure created by a Maven archetype

How Spring MVC handles requests using the Dispatcher Servlet

Basic controller implementation

The role of web.xml and application configuration files

How a traditional Spring MVC application is initialized and executed

**Project Structure**
ArchetypeProject/
 ├── src/main/java/         → Java source files (controllers, config)
 ├── src/main/resources/    → Application resources
 ├── src/main/webapp/       → JSP views, WEB-INF configuration
 ├── pom.xml                → Project dependencies and build configuration
 └── README.md              → Project documentation

Technologies Used

Java

Spring MVC

Servlet API

Maven

JSP

Tomcat or any servlet container

How to Run the Project
1. Build the project
mvn clean install

2. Deploy on Tomcat

Copy the generated WAR file from:

/target/ArchetypeProject.war


Deploy the WAR file in Tomcat using either:

The webapps/ directory
or

The Tomcat Manager interface

3. Start the Server

Access the application at:

http://localhost:8080/ArchetypeProject

What This Project Teaches

How the DispatcherServlet works (Front Controller pattern)

Request-handling flow in Spring MVC

Standard folder structure of a Spring MVC application

How Maven builds and packages Java web applications

How to generate and use archetype-based starter projects

Notes

This is a traditional Spring MVC application, not a Spring Boot application.

Suitable as a starter project for learning Spring before moving to Spring Boot.

Extensions

You can extend this project by adding:

Additional controllers

JSP pages

Form handling

Java-based Spring configuration

Database integration
