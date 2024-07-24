# Hostel Management System

## Overview

The Hostel Management System is a web-based application designed to manage various activities in a hostel. This project uses an Apache server and MySQL 5.62 for data storage. The system is divided into two main modules: Admin Module and User Module.

## Features

### Admin Module

- **Admin Login**: Admin can log in through a login form.
- **Admin Profile**: Admin can manage their own profile and change their password.
- **Courses**: Admin can add, edit, and delete courses.
- **Rooms**: Admin can create rooms, allot seats to particular rooms, and assign fees.
- **Registration**: Admin can create student profiles and allot rooms.
- **Manage the Registration**: Admin can manage all student profiles, print profiles, and delete profiles.
- **Complaints**: Admin can manage all student complaints and take appropriate actions.
- **Feedback**: Admin can view feedback given by students for the hostel.
- **Forgot Password**: Admin can retrieve their password if forgotten.

### User Module

- **User Registration**: Users can register through a user registration form.
- **User Login**: Users can log in through a login form.
- **Forgot Password**: Users can retrieve their password through a forgot password link.
- **User Dashboard**: Users can access their dashboard.
- **User Profile**: Users can manage their own profile.
- **Book Hostel**: Users can book a hostel.
- **Room Details**: Users can view details of the booked room.
- **Complaint Registration**: Users can lodge complaints.
- **Registered Complaint**: Users can check the status of their registered complaints.
- **Feedback**: Users can provide feedback for the hostel.
- **Change Password**: Users can change their own password.
- **User Access Log**: Users can view their last login details.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL 5.62
- **Server**: Apache

## Installation

### Prerequisites

- Apache Server
- MySQL 5.62
- PHP

### Software Requirements

You can use any one of the following:

- WAMP
- XAMPP
- MAMP
- LAMP

### Steps

1. **Download and Unzip the file on your local system.**
2. **Copy the `hostel` folder and place it inside the `xampp/htdocs/` directory.**

### Database Configuration

1. Open PHPMyAdmin.
2. Create a database named `hostel`.
3. Import the `hostel.sql` file into the `hostel` database.
4. Open your browser and navigate to `http://localhost/hostel/index.php`.

### Login Details

- **Admin Login**: Navigate to `http://localhost/hostel/admin/`
  - **Username**: admin
  - **Password**: Test@1234
- **User Login**: 'http://localhost/hostel/index.php' 
  - **Username**: test@gmail.com
  - **Password**: Test@123

## Usage

### Admin

1. Log in through the admin login form.
2. Manage profile, courses, rooms, registrations, complaints, and feedback through the admin dashboard.
3. Use the forgot password feature if necessary.

### User

1. Register through the user registration form.
2. Log in through the user login form.
3. Manage profile, book hostels, view room details, lodge complaints, check complaint status, provide feedback, change password, and view access logs through the user dashboard.
4. Use the forgot password feature if necessary.

## Contributions (Group Members)

- **MT. Arsam (19APC4363)**: Developed the admin module, including admin login, profile management, and course management.
- **MSS. Natha (19APC4073)**: Worked on the user module, focusing on user registration, login, and profile management.
- **ARM. Afraar (19APC3945)**: Set up the database, configured the server, and integrated the frontend with the backend.