# 🚗 Driver Drowsiness Detection System

## 📌 Overview
A real-time computer vision system that detects driver drowsiness using facial landmark detection and triggers an alert when the driver's eyes remain closed for a defined threshold duration.

This system helps prevent road accidents caused by fatigue and inattention.

---

## 🚀 Features
- Real-time webcam monitoring
- Face detection using Haar Cascade
- Facial landmark detection using dlib
- Eye Aspect Ratio (EAR) calculation
- Automatic audio alert when drowsiness detected
- Lightweight and real-time performance

---

## 🛠 Tech Stack
- Python
- OpenCV
- dlib
- NumPy
- SciPy
- playsound

---

## 🧠 How It Works
1. Webcam captures live video frames.
2. Face is detected using Haar Cascade.
3. Facial landmarks are extracted using dlib’s 68-point predictor.
4. Eye Aspect Ratio (EAR) is calculated.
5. If EAR falls below a threshold for consecutive frames → Alert is triggered.

---

## ▶ How to Run

### 1️⃣ Install dependencies
pip install -r requirements.txt

### 2️⃣ Download facial landmark model
Download:
https://github.com/davisking/dlib-models

Place the file:
shape_predictor_68_face_landmarks.dat

inside the project directory.

### 3️⃣ Run the project
python main.py
