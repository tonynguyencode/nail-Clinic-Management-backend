# Backend
This repository contains the application backend built with Spring Boot and Spring Security, following the agile architecture. The project involves developing RESTful API endpoints to provide services for the Nail-Clinic-Management frontend application.

## Features
Services:
    - Customer: Add, modify and delete customer profile.
    - Appointment: Schedule, modify, and cancel appointments.
    - Management: Schedule, modify, and cancel appointments.

Integration:
    - Utilizes Spring Security to provide authentication and role-based security.
    - Implementing services for the endpoint with JPA (Java Persistence API) and EntityManager to implement custom raw SQL queries.

## Workflow
Adding a Customer:
    - Customer initiates a request via the Sign-up UI.
    - Customer management service will process the request and add the customer's profile to the database.

Scheduling an Appointment:
    - User schedules an appointment.
    - Appointments management coordinates the operation and records the appointment.

Management Feature (Currently working on it)
    - View, approve, or deny an appointment.
    - Manually adding, modify and deleting an appointment.

## Architecture
Communication:
    - Spring Boot, Spring Security.
    - RESTful APIs.
    - Docker container.

Data Management
    - MySQL database.
    - Spring JPA.
    - Spring EntityManager for custom raw SQL queries.
