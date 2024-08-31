Automatic Attendance Management System Using Face Recognition 

This project is an Automatic Attendance Management System that uses face recognition to mark attendance. The system employs the Haar Cascade Classifier for face detection and records attendance automatically for recognized individuals.

Features
Face Detection: Detects faces in real-time using the Haar Cascade Classifier.
Face Recognition: Identifies and records attendance for registered individuals.
Database Storage: Attendance records are stored in a local database (e.g., SQLite).
Report Generation: Provides attendance reports.

Requirements
Python 3.x, 
OpenCV for face detection and recognition, 
NumPy for handling arrays, 
SQLite/MySQL for storing attendance records.

Installation:
Clone the repository

Install dependencies:
pip install -r requirements.txt

Run the application:
python main.py

Usage
Register Faces: Capture and register participant faces using the registration module.
Start Attendance: Run the attendance module to automatically record attendance.
View Attendance: Access attendance records stored in the database.
