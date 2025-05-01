# Face Recognition Attendance System 🚀

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-orange)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green)

A modern attendance management system using facial recognition technology with real-time webcam detection and intuitive GUI interface.

## Features 🌟

### Core Functionality
- Real-time face detection & recognition
- Automatic attendance logging to CSV
- 5-minute duplicate entry prevention
- Scrollable face gallery with 6-column grid
- Manual attendance override capability

### Security & Management
- Admin panel with password protection
- Face registration interface with live preview
- Student database management (CSV backend)
- Dark mode UI with hover effects
- Encrypted credential storage

## Installation 💻

1. **Clone Repository**
```bash
git clone https://github.com/taskmasterzoro/face-attendance-system.git
cd face-attendance-system
```
Usage 🖥️
Launch Application

bash
python main.py
Interface Guide
Main Interface

### Button	Functionality
- 🎥 Take Attendance	Start real-time recognition
- 📷 Register New Face	Capture new student profiles
- 📜 View All Faces	Toggle face gallery display
- 📊 Attendance Logs	Show detailed attendance records
- 🔒 Admin Panel	Access database management tools

### System Architecture 🧩
plaintext
face-attendance-system/

├── main.py                 - Main application entry

├── face_recognition_module.py - Core recognition logic

├── ViewFaces.py            - Face gallery management

├── NewStudent.py           - Student registration GUI

├── known_faces/            - Registered face images

├── attendance_logs/        - CSV attendance records

└── student_details/        - Student metadata

### Tech Stack 🔧
Component	Technology
- Face Recognition	face_recognition + dlib
- Computer Vision	OpenCV 4.5+
- GUI Framework	Tkinter with custom themes
- Data Management	pandas + CSV
- Image Processing	Pillow (PIL)
- Async Operations	Threading

Development Roadmap 🗺️

### Next Features
- ☁️ Cloud sync for attendance records
- 📱 Mobile companion app integration
- 🎭 Anti-spoofing with liveness detection
- 📊 Advanced analytics dashboard

### Optimization Goals
- ⚡ Real-time performance improvements
- 🔍 Recognition accuracy enhancements
- 📦 EXE packaging for Windows deployment
