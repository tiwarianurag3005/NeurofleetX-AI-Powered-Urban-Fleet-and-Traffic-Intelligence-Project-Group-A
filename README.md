# NeurofleetX AI Powered Urban Fleet and Traffic Intelligence.


# NeurofleetX: Intelligent Fleet Management & Ride-Booking System
This repository contains the full-stack code for the NeurofleetX application, a modern ride-booking platform. The project is divided into two main parts: a dynamic frontend built with React and a secure backend powered by Java Spring Boot.

# Project Overview
NeurofleetX is designed to serve two primary user roles: Passengers and Fleet Owners.

  Passengers can book immediate rides, schedule rides in advance, and receive smart recommendations based on their travel history.

  Fleet Owners can manage their entire fleet of vehicles, view live operational data, track ride history, and gain insights through analytics.

# Features Implemented
Frontend (React)
  Dual-Role UI: The interface dynamically changes based on whether the user is a "Passenger" or a "Fleet Owner".

Passenger Dashboard:
  Smart ride matching based on vehicle type and passenger count.
  Advance booking system to schedule future rides.
  AI-powered route optimization suggestions.
  Simulated map view with traffic heatmap and route visualization.

Fleet Owner Dashboard:
  Comprehensive fleet management (add, view, and remove vehicles).
  Live vehicle status tracking ("Idle", "On Ride").
  Data visualization with a maintenance status pie chart and ride analytics graphs.
  Ride history table with CSV and PDF export options.

State Management: All frontend data is managed within React's Context API.

Fresh Start: The application is configured to start a new session every time it launches, without loading historical data.

Backend (Java Spring Boot)
  Secure Authentication: Complete user registration (signup) and login (signin) system.
  JWT Security: API endpoints are secured using JSON Web Tokens (JWT), ensuring that only authenticated users can access protected data.
  Database: User credentials and roles are securely stored and managed in a MySQL database.

# Technologies Used

Category  Technology

Frontend: React, Tailwind CSS

Backend: Java 17, Spring Boot, Spring Security, Spring Data JPA

Database: MySQL

Build Tool: Maven

# How to Run the Project

# Backend Setup
1) Configure Database: Update the src/main/resources/application.properties file with your MySQL username and password.

2) Run Application: Execute the main method in NeurofleetxBackendApplication.java.

# Frontend Setup
1) Navigate to Frontend Directory: Open a terminal in your frontend project folder.

2) Install Dependencies: npm install

3) Start Application: npm start
