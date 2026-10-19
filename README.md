# HRMS - Human Resource Management System

A web-based Human Resource Management System built using Java and Spring Boot to manage job postings, job seekers, job applications, enquiries, and feedback.

## 📌 About the Project

HRMS (Human Resource Management System) is a web application designed to simplify recruitment and job management activities. It provides separate interfaces for administrators and job seekers to manage job-related information through a user-friendly interface.

The application uses Java and Spring Boot for backend development, Thymeleaf for server-side rendering, and MySQL for database management.

## ✨ Features

### 👨‍💼 Admin Module
- Admin login and dashboard
- Post and manage job opportunities
- View registered job seekers
- View job application records
- Manage enquiries
- View feedback and complaints
- Manage job postings and submitted records
- Change admin password
- Logout functionality

### 👤 Job Seeker Module
- User registration and login
- Browse available job opportunities
- Apply for jobs
- Access the user dashboard
- View and manage profile information
- Change password
- Submit feedback and complaints
- Logout functionality

### 🌐 Public Pages
- Home page
- About Us page
- Job listings
- User registration
- User login
- Admin login
- Contact Us and enquiry form

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java 17 | Programming language |
| Spring Boot | Backend application framework |
| Spring MVC | Web request handling |
| Spring Data JPA | Database operations |
| Hibernate | Object-relational mapping |
| Thymeleaf | Server-side HTML rendering |
| HTML5 | Web page structure |
| CSS3 | Styling and layout |
| JavaScript | Client-side interactions |
| Bootstrap | UI components and responsive layout |
| MySQL | Relational database |
| Maven | Dependency and build management |
| Git & GitHub | Version control and project hosting |

## 🏗️ Project Structure

```text
hrms/
├── src/
│   └── main/
│       ├── java/com/example/hrms/
│       │   ├── controller/
│       │   ├── dto/
│       │   ├── model/
│       │   ├── repo/
│       │   └── HrmsApplication.java
│       └── resources/
│           ├── static/
│           ├── templates/
│           └── application.properties
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## ⚙️ Prerequisites

Make sure the following are installed:

- Java Development Kit (JDK)
- MySQL Server
- Git (for cloning the repository)

The project includes a Maven Wrapper to help run Maven commands without requiring a separate Maven installation.

## 🚀 Installation and Setup

### 1. Clone the Repository

Open a terminal and run:

git clone https://github.com/gauravpal-dev/hrms.git

Navigate to the project directory:

cd hrms

### 2. Configure the Database

Start MySQL Server and create the database configured for the application.

If the configured database name is `hrmsdb`, execute:

CREATE DATABASE hrmsdb;

### 3. Configure Database Credentials

Open `src/main/resources/application.properties` and verify the database URL, username, password, and other settings.

Use your own local MySQL credentials. Do not publish database passwords or other secrets in a public repository.

### 4. Run the Application

On Windows, run the following command from the project directory:

mvnw.cmd spring-boot:run

Make sure MySQL is running and the database configuration is correct before starting the application.

### 5. Open the Application

If the application is configured to run on port `8181`, open:

http://localhost:8181/index

## 🗄️ Database

MySQL is used for persistent storage of application data, including job postings, registered users, applications, enquiries, and feedback.

Spring Data JPA and Hibernate support database operations and entity mapping.

## 🎯 Learning Objectives

This project demonstrates practical learning in:

- Java and Spring Boot application development
- Spring MVC architecture
- Controller, model, DTO, and repository layers
- Thymeleaf template integration
- MySQL database connectivity
- CRUD operations
- User registration and login workflows
- Session management
- Git and GitHub version control

## 🔮 Future Enhancements

- Advanced job search and filtering
- Resume upload functionality
- Email notifications for job applications
- Pagination for job listings
- Enhanced authentication and authorization
- Improved input validation and application security

## 👨‍💻 Author

**Gaurav Pal**

Java Developer | Spring Boot Learner

## 🔗 Project Repository

[HRMS - GitHub Repository](https://github.com/gauravpal-dev/hrms)

---

⭐ Thank you for visiting this project!
