# Full-Stack E-Commerce Application

A full-stack E-Commerce web application built using Spring Boot (Backend) and React.js (Frontend) that supports complete product management, shopping cart functionality, and order processing with persistent database storage.

This project demonstrates real-world implementation of REST APIs, frontend-backend integration, and database-driven application design.

---

## Features

- Product catalog with full CRUD operations  
- User-friendly shopping cart functionality  
- Order placement and order management  
- RESTful APIs built using Spring Boot  
- Frontend built using React.js  
- Database persistence using Hibernate and JPA  
  - H2 (in-memory) database for development  
  - Easily configurable to MySQL or PostgreSQL  
- Responsive UI for smooth user experience  
- Clean separation of frontend and backend concerns  

---

## Technology Stack

### Backend
- Java 21  
- Spring Boot  
- Hibernate  
- JPA  
- H2 Database (Development) / MySQL or PostgreSQL (Optional)  
- Maven  

### Frontend
- React.js  
- JavaScript  
- npm  

### Tools and Version Control
- Git  
- GitHub  
- REST API Architecture  

---

## Setup Instructions

Follow the steps below to run this project locally.

### Prerequisites

Make sure you have the following installed:

- Java 21  
- Maven  
- Node.js and npm  
- Git  

---

### Backend Setup (Spring Boot)

git clone https://github.com/Avisek9/ecommerce-app.git

cd ecommerce-backend

mvn clean install  

mvn spring-boot:run  

The backend will start on:

http://localhost:8080  

H2 Console:

http://localhost:8080/h2-console  

---

### Frontend Setup (React.js)

cd frontend  
npm install  
npm start  

Frontend will run on:

http://localhost:3000  

---

## API and Database

- All backend services are exposed via REST APIs  
- Hibernate ORM is used for database interaction  
- The application can be easily configured to switch from H2 to MySQL or PostgreSQL using application properties  

---

## Future Enhancements

- User authentication and authorization using Spring Security and JWT  
- Payment gateway integration  
- Admin dashboard  
- Product image uploads  
- Order tracking system  

---

## Author

Abhishek Sahu    

---

If you find this project useful, feel free to give it a star.