##### Airplane Ticket Reservation System

## Overview

The Airplane Ticket Reservation System is a full-stack web application built using Java, AWS, and Spring Boot. The system allows users to search for flights, select seats, make reservations, and process payments. The project aims to provide a seamless and efficient experience for booking airline tickets online.

## Features

User Authentication: Secure login and registration for customers.

Flight Search & Filtering: Find flights based on source, destination, date, and price.

Seat Selection: Choose preferred seats before booking.

Reservation Management: View, modify, or cancel booked tickets.

Payment Integration: Secure payment gateway for hassle-free transactions.

Admin Dashboard: Manage flights, bookings, and user data.

Technologies Used

Backend: Java, Spring Boot

Frontend: React (or other frontend framework if applicable)

Database: PostgreSQL (hosted on AWS RDS)

Cloud Services: AWS S3 (for storing documents/images), AWS Lambda (for serverless functions)

Authentication: Spring Security, JWT

### Setup Instructions

## Prerequisites:

Java 17+

Node.js & npm

Steps to Run Locally:

Clone the Repository:

git clone https://github.com/your-username/airplane-ticket-reservation.git
cd airplane-ticket-reservation

Backend Setup:

Navigate to the backend folder:

## cd backend

Install dependencies and start the Spring Boot server:

./mvnw spring-boot:run

## Frontend Setup:

Navigate to the frontend folder:

cd frontend

## Install dependencies and start the React app:

npm install
npm start

## Future Enhancements

Implement AI-based dynamic pricing

Add multi-city flight booking

Introduce loyalty rewards program

