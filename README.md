# FreePass

<div align="center">

## Free Public Transportation Pass Management System

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-007396?style=for-the-badge&logo=java&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-Template%20Engine-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

**Author:** Georgios Kitsakis

</div>

---

## Overview

FreePass is a full-stack web application for managing free public transportation passes for unemployed citizens. The system connects citizens, OAED (Employment Organization) employees, and OASA (Public Transport) staff through a secure, role-based platform.

## Features

### Multi-Role System

**Citizens:**
- Register and submit applications
- View application status (Waiting/Accepted/Rejected)

**OAED Employees:**
- Review applications
- Approve or reject requests

**OASA Staff:**
- View approved applications
- Generate transportation passes

**Administrators:**
- Create employee accounts
- Manage system users

## Tech Stack

- **Spring Boot 2.7** - Backend framework
- **Spring Data JPA** - Database abstraction
- **Spring Security** - Authentication & authorization
- **MySQL 8.0** - Database
- **Thymeleaf** - Template engine
- **Maven** - Build tool

## Installation

### Prerequisites
- Java 17+
- MySQL 8.0+
- Maven 3.6+

### Setup

1. Clone repository
2. Create MySQL database
3. Configure database connection in application.properties
4. Run application on port 8080

## User Workflows

### Citizens
1. Register at /register
2. Login and submit application
3. Check status on profile page

### OAED
1. Login at /oaed
2. Review applications
3. Accept or reject requests

### OASA
1. Login at /oasa
2. View approved applications
3. Set duration and generate passes

### Admin
1. Login at /admin
2. Create OAED/OASA accounts

## API Endpoints

All endpoints documented in original Greek README. Key endpoints include saving applications, updating status, and managing users with role-based access control.

## Security

- BCrypt password encryption
- Role-based access control
- CSRF protection
- Session management

## Contact

**Georgios Kitsakis**
- Email: kitsakisgk@gmail.com
- GitHub: @kitsakisGk
- LinkedIn: Georgios Kitsakis

---

Built with Spring Boot demonstrating enterprise Java development skills
