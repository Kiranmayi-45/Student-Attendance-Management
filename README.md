# Attendance Management System (MERN Stack)

## Overview
This project is a comprehensive Attendance Management System built using the MERN stack (MongoDB, Express, React, Node.js). It facilitates the management and tracking of attendance for students, teachers, and administrators, with various functionalities tailored to each user role. The system integrates Material UI for design and NodeMailer for sending emails.

## Features

### Student
- **Check Attendance Percentage**: View their attendance percentage.
- **Attendance Requirement**: Calculate the number of classes needed to achieve 75% attendance.
- **Holidays**: View the list of holidays.
- **Announcements**: Check announcements made by teachers.
- **Leave Requests**: Apply for leave to the teacher.

### Teacher
- **Mark Attendance**: Record attendance for different classes and sections.
- **Holidays**: View the list of holidays.
- **Announcements**: Make announcements to students.
- **Manage Leave Requests**: Accept or deny leave requests from students, with email notifications.
- **Attendance Monitoring**: View the list of students with less than 75% attendance and send them emails.

### Admin
- **User Management**: Add students and teachers. Upon successful registration, users receive an email with their username and password.
- **Holidays**: Add holidays to the system.
- **User Information**: View detailed information about students and teachers.
- **User Deletion**: Delete student or teacher accounts.

## Tech Stack
- **Frontend**: React, Material UI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (deployed on MongoDB Atlas)
- **Authentication**: JSON Web Tokens (JWT)
- **Email Notifications**: NodeMailer
