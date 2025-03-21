# University Course Registration System

## Overview
A modern course registration system for students and admins. Students can register for courses, view schedules, and check prerequisites. Admins can manage courses, registrations, and generate reports.

---

## Features

### **Student Features**
- **Login**: Use roll number to log in.
- **Interactive Schedule**: Real-time calendar with conflict detection.
- **Real-Time Seat Availability**: No page refreshes needed.
- **Course Filtering**: Filter by department, time, day, and seats.
- **Prerequisite Visualization**: View course prerequisites.

### **Admin Features**
- **Login**: Use username and password.
- **Course Management**: Add, update, or delete courses.
- **Student Management**: View and override registrations.
- **Seat Management**: Adjust course seats.
- **Reports**: Generate reports on registrations, seats, and prerequisites.

---

## Technologies
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MongoDB

---

## Setup

1. Install [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/).
2. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in `config/`:
   ```env
   MONGO_URI=mongodb://localhost:27017/course-registration
   ```
5. Start the server:
   ```bash
   npm start
   ```
6. Open `http://localhost:5000` in your browser.

---

## Usage

### Student
1. Log in with your roll number.
2. Use the calendar to view and manage your schedule.
3. Filter and register for courses in real-time.

### Admin
1. Log in with your username and password.
2. Manage courses, registrations, and generate reports.

---

## Bonus
- **Seat Notifications**: Subscribe to courses for seat availability alerts.
- **GitHub Repository**: [Link to GitHub Repo](<repository-url>).

---

## Contact
- **Name**: [Your Name]
- **Email**: [Your Email]
- **GitHub**: [Your GitHub Profile]

---
