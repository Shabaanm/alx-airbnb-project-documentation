# Airbnb Clone – Technical and Functional Requirements

This document specifies the functional and technical requirements for core backend features of the Airbnb Clone system.



## 1. User Authentication

###  Functional Requirements
- Allow users to register with name, email, and password
- Allow users to log in and receive an authentication token
- Secure passwords using hashing (e.g., bcrypt)
- Validate uniqueness of email

###  API Endpoints

| Method | Endpoint         | Description        |
|--------|------------------|--------------------|
| POST   | `/api/register`  | Register a new user |
| POST   | `/api/login`     | Authenticate user and return token |

###  Input Specification
