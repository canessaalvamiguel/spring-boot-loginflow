# Login Registration Backend

This backend project implements signUp, email confirmation and login using Spring Boot and Spring Security.

- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

Based on:
https://www.youtube.com/watch?v=QwQuro7ekvc
### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Amigos",
    "lastName": "Code",
    "email": "hellow@amigoscode.com",
    "password": "password"
}'
```