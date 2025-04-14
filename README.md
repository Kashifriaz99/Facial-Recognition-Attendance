# Facial Recognition Attendance System

This project is a Python-based **Facial Recognition Attendance System** that uses your webcam to detect and recognize faces, then marks attendance automatically by recording the recognized names along with timestamps in a CSV file.

## Features

- Real-time face detection and recognition using webcam.
- Automatically logs attendance only once per individual per session.
- Easily extendable by adding more images to the ImagesAttendance/ folder.
- Option to use screen capture instead of webcam (commented in code).

## Tech Stack

- Python
- OpenCV
- face_recognition
- NumPy
- datetime
- os
