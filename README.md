# IT3232 E_COMMERCE(P) Day02-2025/03/21

## Overview
This is a simple Spring Boot application that provides two REST API endpoints. It demonstrates the use of `@RestController`, `@RequestMapping`, and `@GetMapping` annotations.

## Technologies Used
- Java
- Spring Boot
- Maven

## Project Structure
```
lk.ac.vau.fas.ict.Controller
  |-- AppController.java
```

## Setup and Running the Application
### Prerequisites
- Install Java (JDK 8 or later)
- Install Maven
- Install Spring Boot

### Steps to Run
1. Clone the repository or create a new Spring Boot project.
2. Ensure dependencies are installed via Maven.
3. Run the application using:
   ```sh
   mvn spring-boot:run
   ```
4. Access the endpoints in a browser or Postman:
   - `http://localhost:8080/app/msg` → Returns: **Hello SpringBoot**

     ## Output
     ![Screenshot (937)](https://github.com/user-attachments/assets/4df3aad0-9800-4331-9da8-39b3c8b22794)

     
   - `http://localhost:8080/app/name` → Returns: **Hello I am Maleesha**

     ##Output
     ![Screenshot (938)](https://github.com/user-attachments/assets/51b65603-6327-4d42-b4aa-9a3ab7309955)


## Code Explanation
```
- `@RestController` marks this class as a RESTful web service.
- `@RequestMapping("/app")` sets the base URL for the endpoints.
- `@GetMapping("/msg")` maps `/msg` to return "Hello SpringBoot".
- `@GetMapping("/name")` maps `/name` to return "Hello I am Maleesha".

## License
This project is open-source and available for educational purposes.

