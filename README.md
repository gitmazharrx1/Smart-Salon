# Smart-Salon

## Overview

**Smart-Salon** is a modern, fully-featured application designed to streamline the operations of a salon or spa. It provides an intuitive interface for managing appointments, client information, employee schedules, and more. The project aims to improve salon management efficiency and enhance the overall customer experience.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Specification](#project-specification)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Appointment Booking**: Allows clients to book appointments online.
- **Customer Management**: Store and manage customer details, preferences, and visit history.
- **Staff Scheduling**: Assign shifts and manage employee schedules.
- **Payment Integration**: Support for various payment methods.
- **Notifications**: Email and SMS notifications for appointment reminders.
- **Reports & Analytics**: Generate reports for sales, appointments, and client activity.
- **User Authentication**: Secure login and role-based access control for employees and admins.

## Project Specification

### 1. Project Overview
**Smart-Salon** is a comprehensive salon management application designed to streamline operations for salon owners and enhance the experience for clients. It enables online appointment booking, client management, staff scheduling, and reporting, all through a user-friendly interface. The application targets salon owners, staff, and clients, providing features tailored to their needs.

### 2. Objectives
- Simplify salon appointment scheduling and management.
- Improve customer service and client engagement.
- Streamline business operations and staff scheduling.
- Generate useful insights through analytics and reports.

### 3. Scope
- **Frontend**: Web application for clients, staff, and admin users.
- **Backend**: API services for handling business logic and data processing.
- **Database**: Storage for client data, appointments, services, staff schedules, etc.
- **Notifications**: Real-time updates and reminders via email or SMS.

### 4. Functional Requirements

#### 4.1 User Roles
- **Admin**:
  - Manage salon services (add, update, delete services).
  - Manage employee schedules and availability.
  - View and generate sales reports and client activity analytics.
  - Handle user roles and permissions.
- **Staff**:
  - View and update their schedule.
  - Check client appointments and manage them.
  - Update service status (e.g., service completed).
- **Client**:
  - Book appointments online.
  - View booking history and manage appointments.
  - Receive notifications for upcoming appointments and promotions.

#### 4.2 Appointment Management
- Online booking form for clients.
- Calendar view for admins and staff to view all scheduled appointments.
- Appointment rescheduling and cancellation options.

#### 4.3 Service Management
- Create and update a list of services offered (e.g., haircut, manicure, spa).
- Set service duration and pricing.

#### 4.4 Notifications and Reminders
- Send automated email and SMS reminders to clients for upcoming appointments.
- Notify staff about changes in their schedule or new appointments.

#### 4.5 Reports & Analytics
- Sales reports showing revenue trends.
- Appointment analysis for peak times and popular services.
- Client activity reports to identify regular and high-value customers.

### 5. Non-Functional Requirements
- **Performance**: The system should handle multiple concurrent users without performance degradation.
- **Scalability**: The application must support the growth of the business, handling increasing data and user traffic.
- **Security**: Implement role-based access control, data encryption, and secure payment processing.
- **Usability**: The application should provide a simple, intuitive interface for all user roles.

## Tech Stack

### Frontend
- **Angular 18**: TypeScript framework for building a responsive UI.
- **Bootstrap 5**: For styling and responsive design.
- **Ngx-Translate**: For multi-language support.

### Backend
- **.NET Core**: API and server-side logic.
- **SignalR**: For real-time updates (e.g., notifications).
- **Entity Framework Core**: For database management.

### Database
- **SQL Server**: For storing salon data.

### Other Tools
- **GitHub Actions**: CI/CD pipeline.
- **Docker**: Containerization for deployment.

## Installation

### Prerequisites
- **Node.js** (v18 or higher)
- **Angular CLI** (v18 or higher)
- **.NET Core SDK** (v7 or higher)
- **SQL Server**
