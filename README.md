This project is the result of the Pluralsight course [Spring Framework: Creating Your First Spring Boot Application](https://app.pluralsight.com/library/courses/creating-first-spring-boot-application/table-of-contents).

For DB setup, refer to [dlbunker/ps-first-spring-boot-app](https://github.com/dlbunker/ps-first-spring-boot-app).

OS environment variables to be provided at startup when `PersistenceConfiguration` is not being used:
```
DB_URL=jdbc:postgresql://localhost:5432/conference_app;DB_USERNAME=postgres;DB_PASSWORD=Welcome;
```