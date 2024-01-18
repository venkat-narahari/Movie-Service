# Movie Service

An Experimental CRUD API Microservice that interacts with different databases to query, save and update movies.

## Technologies and Tools

- [SpringBoot2](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Maven](https://maven.apache.org/guides/index.html)
- [SpringDataJPA](https://spring.io/projects/spring-data-jpa/)
- [Java8](https://docs.oracle.com/javase/8/docs/)

## Project Structure

- `src/main/java`: Contains the Java source code. 
  - `com.stackroute.movieservice`: Main package for the application.
    - `MovieServiceApplication.java`: Main class to run the Movie service application. 
    - `controller/`: Package for controllers handling web HTTP requests. 
    - `domain/`: Package for data models/entities. 
    - `repository/`: Package for data access repositories. 
    - `services/`: Package for business logic services. 
    - `config/`: Package for configurations such as databases here.
- `src/main/resources`: Contains application properties and static resources. 
  - `application.properties`: Configuration file for Spring Boot.

## How to Run

1. Java 8 and Maven 2 needs to be installed and set up the environment variables set.
2. Clone this repository.
3. Navigate to the project directory: `cd Movie-Service`.
4. Make sure the application properties are correct with your up and running database.
5. Build the project to download necessary dependencies: `mvn compile`.
6. Run the application: `mvn spring-boot:run`.

## Configuration

- Database configuration is in application.properties. You can change the database settings if needed.
- Additional configurations can be added to application.properties for customizing the application.

## Additional Notes

- The current project is to understand the basics of building Spring APIs, webservices and microservices.
- Add Unit and Integration tests to make the quality of application better.
- Add docker file to streamline required environment for the application directly without modifying local environment.