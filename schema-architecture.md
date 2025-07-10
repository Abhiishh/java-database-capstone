# Architecture Summmary
This Spring Boot application uses both MVC and REST controllers. Thymeleaf templates are used for the Admin and Doctor dashboards, while REST APIs serve all other modules. The application interacts with two databases—MySQL (for patient, doctor, appointment, and admin data) and MongoDB (for prescriptions). All controllers route requests through a common service layer, which in turn delegates to the appropriate repositories. MySQL uses JPA entities while MongoDB uses document models.

# Numbered flow of data and control
1. User Interface Layer
2. Controller Layer
3. Service Layer
4. Repository Layer
5. Database access
6. Model binding
7. Application models in use 
