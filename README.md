# Springboot Project on Registration and Login Services and interaction between them using API calls and objects

This project demonstrates a microservices-based approach to handling user registration and login functionalities using Spring Boot. Each service operates independently and communicates via RESTful API calls, with shared data structures (DTOs) to ensure consistency and modularity.

🔧 Features
🧍 User Registration Service

Accepts user sign-up requests

Validates and stores user information securely

Communicates with the Login service as needed

🔐 User Login Service

Authenticates user credentials

Issues authentication responses (e.g., tokens if implemented)

Interacts with the Registration service to retrieve user details

🔗 Inter-Service Communication

REST API-based communication between services

DTOs used for structured data exchange

🛠️ Tech Stack
Java 17+

Spring Boot

Spring Web

REST APIs


