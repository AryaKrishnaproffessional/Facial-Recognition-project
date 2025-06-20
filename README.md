# Facial-Recognition-project

# 🎯 Real-Time Face Recognition & Access Control System

Welcome to a real-time face recognition system built with TensorFlow and OpenCV. This project enables webcam-based identity verification using a trained face classifier and can optionally detect facial emotion using DeepFace.

> "If you're in the system, you're in. If not, access denied."

---

## 🧠 Overview

This project functions as a lightweight facial authentication system:
- Captures a face via webcam
- Uses a trained CNN classifier (or MobileNetV2) to identify the user
- Grants access only to known individuals
- Optional: detects facial emotion live
- Can be extended with logging, voice feedback, and hardware access control

---

## ⚙️ Tech Stack

- Python 3.9+
- TensorFlow / Keras
- OpenCV
- DeepFace (for emotion detection)
- Pandas, NumPy, Matplotlib
- LFW dataset or custom face images

---

## 📁 Project Structure

facial-recognition-access-control/
│
├── dataset/
│ ├── Aryak/ # Your personal face images
│ ├── Person_X/ # Other known identities
│
├── model_training.py # Model training script (CNN or MobileNetV2)
├── access_control.py # Real-time webcam-based identity verification
├── emotion_detector.py # Optional: real-time emotion detection via DeepFace
├── utils.py # Shared helpers (e.g., predict_person, plotting)
├── requirements.txt
└── README.md
