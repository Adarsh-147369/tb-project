# TalentBridge - Internal Job Portal

## Overview
TalentBridge is an internal job portal designed to facilitate employee mobility within the organization. This application provides a centralized platform for employees to explore and apply for internal job opportunities while enabling HR to manage job postings and applications efficiently.

## Technologies Used

### Backend (Spring Boot)
- Java 11+
- Spring Boot 2.7.x
- Spring Security
- Spring Data JPA
- Hibernate
- MySQL Database
- Maven (Dependency Management)
- JWT for Authentication

### Frontend (React)
- React 18+
- React Router
- Axios for API calls
- Material-UI (MUI) for UI components
- Redux for state management
- Formik for forms
- Yup for validation

## Features

### Employee Features
- Browse and search job listings with filters (department, location, skills)
- Apply for positions with resume upload
- Track application status
- Manage profile and skills
- Receive notifications for new jobs and application updates

### HR/Manager Features
- Create and manage job postings
- Review and process applications
- Update candidate status (screening, interview, offer)
- Schedule interviews with automated notifications
- Generate reports on internal mobility

## Setup Instructions

### Prerequisites
- Java JDK 11+
- Node.js 16+
- MySQL 8.0+
- Maven
- IDE (IntelliJ IDEA, VS Code, Eclipse)

### Backend Setup
1. Clone the repository
2. Configure MySQL database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/talentbridge
   spring.datasource.username=your_username
   spring.datasource.password=your_password

### Build and run the Spring Boot application:
- mvn clean install
- mvn spring-boot:run
## Frontend Setup
### Navigate to the frontend directory:
- cd frontend
## Install dependencies:
- npm install
## Start the development server:
- npm start
### Environment Variables
- REACT_APP_API_BASE_URL=http://localhost:8080
- REACT_APP_JWT_SECRET=your_jwt_secret
- jwt.secret=your_jwt_secret
- jwt.expiration.ms=86400000
### Deployment
## Backend
- mvn clean package
- java -jar talentbridge-backend.jar
## Frontend
- npm run build
### License
- this project is created by me and the project idea is from sasken technologies as a part of the intership 
### Contact
- For support or questions, please contact Email :- adarshreddy532@gmail.com

