# Hello World Spring Boot Application

This is a simple Spring Boot application that demonstrates a basic "Hello World" endpoint with Spring Security implemented. 

## Features

- A RESTful endpoint that returns "Hello World!"
- Basic authentication using Spring Security
- Dependencies managed with Spring Initializer

## Requirements

- Java 8 or higher
- Maven
- Git

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/helloworldapplication.git
    ```
2. Navigate to the project directory:
    ```sh
    cd helloworldapplication
    ```
3. Build the project using Maven:
    ```sh
    mvn clean install
    ```

## Running the Application

1. Navigate to the project directory:
    ```sh
    cd helloworldapplication
    ```
2. Run the application:
    ```sh
    mvn spring-boot:run
    ```
3. The application will start on `http://localhost:8080`.

## Accessing the Endpoint

The "Hello World" endpoint can be accessed at:

http://localhost:8080/hello-world


## Authentication

This application uses basic authentication. Use the following credentials to access the secured endpoint:

- Username: `helloworld`
- Password: `bye`

Dependencies
The following dependencies are used in this project:
spring-boot-starter-web: For building web applications, including RESTful applications using Spring MVC.
spring-boot-devtools: Provides fast application restarts, LiveReload, and configurations for enhanced development experience.
spring-boot-starter-security: Provides security services for your application.
spring-boot-starter-test: Starter for testing Spring Boot applications with libraries including JUnit, Hamcrest, and Mockito.

