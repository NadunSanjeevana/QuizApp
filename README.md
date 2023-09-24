# Spring Boot Quiz App 


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Setup](#database-setup)


## Introduction

Welcome to the Spring Boot Quiz App backend! This application provides the backend services for a quiz application. It allows you to manage quizzes, questions, and user responses.

## Features

1. **Quiz Management:** Create, read, update, and delete quizzes.
2. **Question Management:** Add, edit, and remove questions within quizzes.
3. **User Responses:** Capture and evaluate user responses to quiz questions.
4. **Security:** Implement authentication and authorization for API endpoints (e.g., JWT).

## Technologies Used

- **Spring Boot:** The primary framework for building the backend.
- **PostgreSQL:** The database used to store quiz and question data.
- **Spring Security:** For securing API endpoints.

## Database Setup

1. Install PostgreSQL and create a new database.
2. Update the `application.properties` file with your database configuration.

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/your-database
spring.datasource.username=your-username
spring.datasource.password=your-password

