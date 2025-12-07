# Full-Stack E-Commerce Application

A full-stack E-Commerce web application built using Spring Boot (Backend) and React.js with Vite (Frontend) that supports complete product management, keyword-based product search, shopping cart functionality, and order placement with persistent database storage.

This project demonstrates real-world implementation of REST APIs, frontend-backend integration, and database-driven application design.

---

## Features

- Product catalog with full CRUD operations  
- Keyword-based product search  
- User-friendly shopping cart functionality  
- Order placement system  
- RESTful APIs built using Spring Boot  
- Frontend built using React.js with Vite  
- Database persistence using Hibernate and JPA  
  - H2 (in-memory) database for development  
  - Easily configurable to MySQL for production  
- Responsive UI for smooth user experience  
- Clean separation of frontend and backend concerns  

---

## Technology Stack

### Backend
- Java 21  
- Spring Boot  
- Hibernate  
- JPA  
- H2 (Development) / MySQL (Production - Optional)  
- Maven  

### Frontend
- React.js (Vite)  
- JavaScript  
- npm  

### Tools and Version Control
- Git  
- GitHub  
- Postman (API Testing)  

---

## Setup Instructions

Follow the steps below to run this project locally.

### Prerequisites

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

H2 Console (Optional):

http://localhost:8080/h2-console  

---

### Frontend Setup (React.js with Vite)

cd ecommerce-frontend

npm install 

npm run dev  

Frontend will run on:

http://localhost:5173  

---

## API and Database

- All backend services are exposed via REST APIs  
- Hibernate ORM is used for database interaction  
- Search APIs allow filtering products by keyword  
- The application can be easily configured to switch from H2 to MySQL using application properties  

---

## Future Enhancements

- User authentication and authorization using Spring Security and JWT  
- Payment gateway integration  
- Admin dashboard  
- Product image uploads  
- Order tracking system  
- Advanced search and filtering  

---

## Author

Abhishek Sahu  

---

If you find this project useful, feel free to give it a star.
