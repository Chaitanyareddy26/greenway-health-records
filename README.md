# Greenway Health Records

Greenway Health Records is a healthcare data management system designed to handle electronic medical records (EMR), patient data and appointment scheduling with high performance and reliability. The project uses Java Spring Boot with Hibernate (JPA) for persistence, RESTful APIs for integration, and optimized SQL queries for tuning and performance.

## Tech Stack

- **Java 17** – core programming language.
- **Spring Boot & Spring Data JPA** – rapid application development and data access.
- **Hibernate** – ORM framework for database interactions.
- **REST APIs** – integration endpoints for EMR and scheduling systems.
- **MySQL / PostgreSQL** – relational databases.
- **Docker & Kubernetes** – containerization and orchestration.
- **JUnit & Mockito** – testing.

## Architecture

The application follows a layered architecture with controllers, services, repositories and entities. Hibernate manages the persistence layer while service classes implement business logic. APIs are exposed via Spring MVC controllers. The system is containerized using Docker and orchestrated on Kubernetes for scalability.

## Features

- Patient registration and demographics management.
- Appointment scheduling with provider availability.
- Medical record CRUD operations using RESTful endpoints.
- Data validation and transaction management.
- Performance tuned queries for large datasets.
- Dockerized deployment with environment configurations.

## Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Chaitanyareddy26/greenway-health-records.git
   ```
2. Navigate into the project and build using Maven:
   ```bash
   mvn clean install
   ```
3. Run the Spring Boot application:
   ```bash
   mvn spring-boot:run
   ```
4. The application will start on `http://localhost:8080`. Use Postman or curl to interact with REST endpoints defined in `controllers`.

### Docker

You can also run the application in a container using Docker:
```bash
docker build -t greenway-health-records .
docker run -p 8080:8080 greenway-health-records
```

## My Role & Impact

As a Senior Java Developer, I led the migration of legacy healthcare applications to Spring Boot microservices, implemented Hibernate entities and repositories, optimized SQL queries to improve response times by 40%, and designed REST APIs that handle thousands of concurrent requests. I worked closely with database administrators to tune indexes and queries for performance and reliability.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
