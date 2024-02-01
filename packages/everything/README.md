# CENG453 20231 Group11 Backend

This is the Group11 backend application of the CENG453 Term Project. In this backend application, Java 17 is used with Spring Boot v3.1.5. For documentation Springdoc Swagger-ui is utilized. JUnit v4.13.2 is used while creating the unit tests.

## How to run the application

After cloning the project to your local machine, in the project directory, use `mvn clean install` command on your terminal to build the backend application. Then use `java -jar target/CENG453_20231_Group11_backend-0.0.1-SNAPSHOT.jar` to run the application that you built.

## Database

There are 3 entities in the project which are 'user', 'score', and 'password_reset_token'. 

![ER diagram](https://github.com/berke-a/CENG453_20231_Group11_backend/assets/57680495/63b0d705-f334-42b5-8ce3-2cd4f6e64d70)

## Existing Users

There are 5 different users which can be used to use functions requiring authentication. This users are:

| Username | Password |
| -------- | -------- |
| admin   | admin   |
| user1   | password1   |
| user2   | password2  |
| user3   | password3   |
| user4   | password4   |
| user5   | password5   |

## Documentation

There are two ways to reach the API documentation of the project:
- `http://localhost:8080/swagger-ui/index.html` can be used after running the application as stated above. 
- `https://ceng453-20231-group11-backend.onrender.com/swagger-ui/index.html#/` is also available which uses Render for hosting.
