# Online Learning Management System (LMS)

The Online Learning Management System (LMS) is a web application that helps manage online courses. It allows admins, teachers, and students to use the platform for learning, teaching, and tracking progress.

## Technologies Used

### Backend
- Language: Java 17
- Framework: Spring Boot
- Database: MySQL / PostgreSQL
- Testing: JUnit, Mockito

### Frontend
- Framework: React.js

### Tools
- Postman
- Git & GitHub

## Installation & Running the Project

### Backend (Spring Boot)

1. Open terminal and run:
   
```bash
cd lms-backend/lms
```
2. Start the backend server:

```bash
mvn spring-boot:run
```

> Note: Make sure your MySQL/PostgreSQL service is running and the database configuration is correctly set in the `application.properties` file.

### Frontend (React.js)

1. Open a new terminal and run:

```bash
cd lms-frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the frontend development server:

```bash
npm run dev
```

## Features Implemented

- User roles: Admin, Student, Instructor
- Course registration and management
- User progress tracking
- Quiz management system
- Frontend portal for admin and students




