# 🚀 AI Object Detection System

An end-to-end AI-powered Object Detection System built using **YOLOv11**, **FastAPI**, **React.js**, and **OpenCV**. The application performs real-time object detection using a webcam and processes uploaded videos with high-speed YOLO inference.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-009688?logo=fastapi)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![YOLO](https://img.shields.io/badge/YOLO-Ultralytics-red)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📌 Overview

This project demonstrates a complete AI-powered web application capable of detecting multiple objects in:

- 📷 Live Camera Stream
- 🎥 Uploaded Video Files

The frontend is developed using **React.js**, while the backend is built with **FastAPI**. The object detection pipeline uses the **Ultralytics YOLOv11** model for fast and accurate inference.

---

# ✨ Features

## 🎥 Live Camera Detection

- Real-time webcam object detection
- Continuous frame processing
- High-speed YOLO inference
- Bounding boxes
- Class labels
- Confidence scores

---

## 📁 Video Upload Detection

- Upload MP4 videos
- Frame-by-frame processing
- Automatic object detection
- Download processed video
- Browser-compatible output

---

## ⚡ FastAPI Backend

- REST API
- Swagger UI
- Modular architecture
- Video processing service
- Camera frame API

---

## 🧠 AI Model

- YOLOv11 Nano
- Ultralytics
- Multiple object detection
- Real-time inference

---

# 🏗️ Tech Stack

## Frontend

- React.js
- JavaScript
- HTML5
- CSS3
- Material UI

## Backend

- FastAPI
- Python
- Uvicorn
- OpenCV
- NumPy

## AI

- YOLOv11
- Ultralytics

---

# 📂 Project Structure

```text
AI-Object-Detection-System
│
├── backend
│   ├── app
│   │   ├── api
│   │   ├── services
│   │   ├── models
│   │   ├── utils
│   │   ├── config
│   │   └── main.py
│   │
│   ├── weights
│   ├── temp
│   ├── run.py
│   └── requirements.txt
│
├── frontend
│   ├── public
│   ├── src
│   └── package.json
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Object-Detection-System.git
```

```bash
cd AI-Object-Detection-System
```

---

# 🔧 Backend Setup

```bash
cd backend
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate

### Windows

```bash
venv\Scripts\activate
```

### Linux/macOS

```bash
source venv/bin/activate
```

Install Packages

```bash
pip install -r requirements.txt
```

Run Backend

```bash
python run.py
```

Backend URL

```
http://localhost:8000
```

Swagger Documentation

```
http://localhost:8000/docs
```

---

# 💻 Frontend Setup

```bash
cd frontend
```

Install Packages

```bash
npm install
```

Run

```bash
npm start
```

Frontend URL

```
http://localhost:3000
```

---

# 📡 API Endpoints

## Health Check

```
GET /health
```

---

## Live Camera Detection

```
POST /api/v1/detect/frame
```

---

## Video Detection

```
POST /api/v1/detect/video
```

---

# 🖼️ Screenshots

## Home Page

> Add Screenshot Here

---

## Live Camera Detection

> Add Screenshot Here

---

## Video Detection

> Add Screenshot Here

---

## Output Video

> Add Screenshot Here

---

# 🎬 Demo

Add a GIF or YouTube Demo here.

Example:

```
https://youtu.be/your-demo-video
```

---

# 🚀 Future Improvements

- Image Upload Detection
- Object Tracking (ByteTrack / DeepSORT)
- Custom YOLO Training
- GPU Acceleration
- AWS Deployment
- Docker Deployment
- User Authentication
- Detection History
- Analytics Dashboard

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Siddharth Jagadale**

- GitHub: https://github.com/Siddharth3007Git
- LinkedIn: *(Add your LinkedIn profile URL)*

---

# ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.
