# Ticket Force

Pet project - ticket management application  
Allows tracking project status and create project tasks  
Supports 3 user role types: admin, manager and employee  

## Functionalities
- secure login
- user creation
- project creation
- task creation
- assigning user with roles, projects, tasks
- tasks status tracking
- projects status tracking

## Technologies
- SpringBoot
- PostgreSQL
- Thymeleaf

## Usage
To run locally -> <br>
Clone the repo <br>
Input DB credentials in ```application.properties``` to connect to your local database
```java
spring.datasource.url=YOUR_DATASOURCE
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```
Import project in IDE (preferably InteliJ IDEA) and run ```SpringMvcProjectManagementApplication``` <br>

Go to ```http://localhost:8080/``` in your browser (you can switch ports in Dockerfile)







