# AttendEase – AI Face Recognition Attendance System

<p align="center">
  <img width="290" height="80" alt="AttendEase" src="https://github.com/user-attachments/assets/18f6c229-4bda-4c21-b791-4ee18e2ccdc3" />
</p>

**AttendEase** is an AI-powered face recognition attendance system built using **Django**, **DeepFace (FaceNet)**, and **OpenCV**.  
It provides secure, real-time attendance automation with face verification, anti-spoofing, and role-based access through a modern admin dashboard.

> **Tech Stack:** Django · DeepFace (FaceNet) · OpenCV · Jazzmin · HTML · CSS · JavaScript

---

## Overview

AttendEase is a full-stack intelligent attendance automation platform designed for educational institutes and organizations.  
It leverages **deep learning–based face embeddings** to ensure accurate and secure attendance marking with real-time webcam verification.

---

## Core Features

- AI-based **Face Recognition** using DeepFace (FaceNet)
- **Real-time webcam attendance** marking
- **Liveness detection / anti-spoofing**
- Secure master-face verification
- IN / OUT time-based attendance tracking
- User & Admin role separation
- Leave management system
- Attendance export (CSV / PDF)
- Clean, modern admin dashboard (Jazzmin)

---

## AI & Computer Vision

- Face embedding generation using **FaceNet**
- Face similarity matching via DeepFace
- Real-time face detection with OpenCV
- Anti-spoofing using live camera feed
- Master-face validation enforced by admin

---

## User Portal

- User registration & authentication
- Face enrollment & verification
- Attendance marking
- Attendance history view
- Leave application
- Profile management
- Attendance download (CSV / PDF)

---

## Admin Dashboard (Jazzmin)

- Approve or reject user registrations
- Upload and manage master face data
- Manage students / employees
- Leave request approvals
- Attendance monitoring & analytics
- Export attendance reports

---

## Screenshots

### Landing Page
<p align="center">
  <img src="https://github.com/user-attachments/assets/de6da535-f86a-4315-a29c-66527c078409" width="800"/>
</p>

### Admin Dashboard
<p align="center">
  <img src="https://github.com/user-attachments/assets/fd5eb022-6f4d-4dc2-a0c2-7ad3905fb48d" width="800"/>
</p>

### User Dashboard
<p align="center">
  <img src="https://github.com/user-attachments/assets/a01975f3-d9c7-4a8c-ad60-820e106b4042" width="800"/>
</p>

---

## Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/Master-Dev201/Attendease.git
cd Attendease
````

### 2. Create Virtual Environment

```bash
python -m venv env

# Linux / Mac
source env/bin/activate

# Windows
env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Create Admin User

```bash
python manage.py createsuperuser
```

### 6. Run Server

```bash
python manage.py runserver
```

---
