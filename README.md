📱 Smart Attendance Tracker App

A modern Android application that helps students track, manage, and analyze their attendance efficiently.
It simplifies attendance management with real-time calculations, visual indicators, and detailed reports.

🚀 Overview

The Smart Attendance Tracker App is designed to solve the common problem of manually tracking attendance.
It allows students to maintain records for multiple subjects, monitor attendance percentage, and take timely action to avoid shortages.

✨ Key Features
🔐 User Authentication
Secure login and registration system
📚 Subject Management
Add subjects with name, code, and teacher
✅ Attendance Marking
Mark attendance as Present or Absent
Supports backdated entries
📊 Automatic Calculation
Real-time attendance percentage
🎨 Visual Status Indicators
🟢 Safe (≥ 75%)
🟡 Warning (60–74%)
🔴 Critical (< 60%)
📈 Detailed Reports
Subject-wise attendance breakdown
Progress bars and statistics
📅 Date-wise Tracking
View complete attendance history
🔒 Offline & Secure
Data stored locally using SQLite
🛠️ Tech Stack
Technology	Purpose
Java	Core application development
Android Studio	Development environment
SQLite	Local database storage
SharedPreferences	Session management
📱 App Workflow
User Login/Register
        ↓
Add Subjects
        ↓
Mark Daily Attendance
        ↓
Automatic Percentage Calculation
        ↓
View Dashboard & Reports
🗂️ Project Structure
SmartAttendanceTracker/
│
├── app/
│   ├── java/com/example/
│   │   ├── activities/
│   │   ├── adapters/
│   │   ├── database/
│   │   └── utils/
│   │
│   ├── res/
│   │   ├── layout/
│   │   ├── drawable/
│   │   └── values/
│   │
│   └── AndroidManifest.xml
│
├── screenshots/
└── README.md
📊 Database Design

The app uses SQLite with three main tables:

Users
Stores user credentials
Subjects
Stores subject details
Attendance
Stores date-wise attendance records

✅ Advantages
Easy and user-friendly interface
Works completely offline
Saves time and effort
Helps maintain required attendance
⚠️ Limitations
Android-only application
No cloud backup functionality
