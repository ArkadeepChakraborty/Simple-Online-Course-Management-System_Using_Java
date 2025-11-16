# Simple-Online-Course-Registration-System
📚 CPC Education – Admin & Student Portal

A complete full-stack learning management system built with Spring Boot, JWT Authentication, React.js, and Tailwind CSS.

<p align="center"> <img src="https://img.shields.io/badge/Java-17-blue" /> <img src="https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen" /> <img src="https://img.shields.io/badge/React-18-blueviolet" /> <img src="https://img.shields.io/badge/MongoDB-Database-success" /> <img src="https://img.shields.io/badge/JWT-Authentication-orange" /> </p>
🚀 Project Overview

This repository contains two frontends and one backend:

🛠 Admin Portal

Add / Edit / Delete Courses

Dashboard

🎓 Student Portal

Browse all courses

Search courses

View enrolled courses

Update profile & password

Login with JWT

⚙ Backend (Spring Boot)

Student APIs

Course APIs

JWT Authentication

Password encryption

Search & filter support


🧩 Tech Stack
Frontend

React.js

React Router

Axios

Tailwind CSS

Backend

Spring Boot

Spring Security + JWT

Hibernate

MySQL

🔑 API Documentation
👨‍🎓 Student APIs

Register Student

POST /student/save

Login Student (JWT Token)

POST /student/login

Get All Students

GET /student/getallstudents

Update Profile

POST /student/updateProfile/{id}

Update Password

POST /student/updatePassword

Delete Student

DELETE /student/deleteStudentById/{id}

📘 Course APIs

Add Course

POST /course/save

Get All Courses

GET /course/getallcourses

Search Course

GET /course/search/{name}

Update Course

POST /course/update/{id}

Delete Course

DELETE /course/deleteCourseById/{id}

Get Enrolled Courses

GET /course/enrolled/{studentId}

🙌 Contributing

Pull requests are welcome!

Feel free to open issues for new features or bug reports.
