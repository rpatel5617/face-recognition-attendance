# 🎯 Face Recognition Attendance System

**Technologies:** Python, OpenCV, Machine Learning  

---

## 🧠 Overview
This project automates the student attendance process using face detection and recognition technology.  
It captures multiple images of each student, stores them with their enrollment details, and marks attendance automatically when a face is recognized.  

The goal of this system is to **eliminate manual attendance errors**, **improve accuracy**, and **save time** using real-time computer vision and machine learning techniques.

---

## ⚙️ Functional Workflow

1. **Student Registration:**  
   - The system captures multiple face images of each student using the webcam.  
   - Each student’s images are stored in a **dedicated folder** on the local system, labeled with their **enrollment number and name**.  
   - Multiple samples help increase recognition accuracy.

2. **Model Training:**  
   - The stored face images are processed and encoded using OpenCV and facial recognition models.  
   - The trained data is then saved for real-time recognition.

3. **Attendance Marking:**  
   - When the system starts attendance mode, it scans faces in real time using the webcam.  
   - Once a face is recognized, the system records the **student’s name, enrollment number, date, and time** in an attendance file (CSV or database).  
   - Duplicate entries for the same day are avoided.

4. **Output:**  
   - A daily attendance record is automatically generated and stored locally.  

---

## 🔍 Key Features
- Real-time face detection and recognition  
- Separate image folders for each student  
- Automatic attendance marking with timestamp  
- Easy scalability for large classrooms  
- Eliminates manual data entry errors  

---

## 🧩 Tools & Technologies
| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Libraries | OpenCV, NumPy, face_recognition |
| Concepts | Machine Learning, Computer Vision, Data Preprocessing |
| Storage | Local file system, CSV (for attendance logs) |

---

## 📈 Project Highlights
- Improved accuracy through multi-image registration per student  
- Fully automated attendance system without manual input  
- Demonstrated use of **Python ML libraries** and **OpenCV** for real-world automation  

---

## 🚀 Future Enhancements
- Integrate database backend (MySQL / MongoDB)  
- Add admin dashboard for viewing attendance reports  
- Implement cloud storage for attendance data  
- Deploy as a standalone desktop or web-based application  

---

## 📎 Note
This repository serves as a **portfolio documentation** of the project.  
Source code and dataset are not included due to storage limitations and privacy concerns.

📧 **Contact:** prutvik5617@gmail.com
🔗 **LinkedIn:** linkedin.com/in/rutvik-patel-38631b189  
🔗 **GitHub:**  https://github.com/rpatel5617
