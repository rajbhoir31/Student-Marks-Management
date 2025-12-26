# MarkProject - Spring Boot

This project is a Spring Boot application designed for managing and tracking student marks. The application includes CRUD operations for handling student data and marks, utilizing Spring Boot's robust framework.

## Features
- **Languages:** Java (Spring Boot)
- **Database:** H2 (Embedded database)
- **Build Tool:** Maven
- **Architecture:** REST API-based structure for interacting with marks and student records
- **Dependency Injection:** Spring Framework

## Tech Stack
- **Spring Boot:** Simplifies application development with Java, providing built-in tools for dependency injection, embedded servers, and REST APIs.
- **H2 Database:** Lightweight in-memory database used for rapid development and testing.
- **Maven:** Handles project dependencies and builds.
- **Spring Data JPA:** Provides easy integration with databases using Java Persistence API (JPA) for object-relational mapping.

## Project Structure
```bash
C:.
├───.idea
├───markproject
│   ├───src
│   │   └───main
│   │       └───java
│   │           └───com
│   │               └───simplogics
│   │                   └───markproject
│   │                       ├───controller
│   │                       ├───model
│   │                       ├───repository
│   │                       └───service
└───target
```
- **Controller:** Handles API requests.
- **Model:** Defines the entities for marks and students.
- **Repository:** Manages database interactions.
- **Service:** Implements business logic for mark operations.

### Endpoints
- `POST /marks`: Add a new mark.
- `GET /marks`: Retrieve all marks.
- `GET /marks/{id}`: Retrieve a specific mark by ID.
- `PUT /marks/{id}`: Update a specific mark.
- `DELETE /marks/{id}`: Delete a specific mark by ID.
