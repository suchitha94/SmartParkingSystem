Smart Parking System

Overview

The Smart Parking System is a web-based application built using Spring Boot to manage parking spaces efficiently. It provides functionalities such as user authentication, parking slot management, fee calculation, and secure user management.

Features

User Authentication (Login, Registration, Role-based access)

Add, Update, Delete Parking Slots

View Available Parking Slots

Calculate Parking Fees Based on Slot Type and Duration

Secure User Management

Admin Panel for Parking Management

Technologies Used

Backend: Java, Spring Boot, Spring MVC, Spring Security

Frontend: HTML, CSS, Bootstrap, JavaScript

Database: MySQL

Build Tool: Maven

ORM: Hibernate (JPA)

Installation Steps

Clone the repository:

git clone https://github.com/yourusername/smart-parking-system.git

Navigate to the project directory:

cd smart-parking-system

Configure the database in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/parking_db
spring.datasource.username=root
spring.datasource.password=yourpassword

Build and run the application:

mvn spring-boot:run

Access the application at http://localhost:8080

Database Schema

Users (id, name, email, password, role)

Parking Slots (id, slot_number, status, type, price_per_hour)

Bookings (id, user_id, slot_id, start_time, end_time, total_fee)

API Endpoints

Method

Endpoint




Authenticate user

Future Enhancements

Real-time slot availability updates

Payment gateway integration

Mobile app support

License

This project is licensed under the MIT License.

Contributors

Your Name - Suchitha

Feel free to contribute! Fork the repo and submit a pull request.

Contact

For any queries, contact saisuchithab@gmail.com.
