# 👤 Face Recognition System using OpenCV (Python)
## 📌 Introduction:

+ The Face Recognition System is a computer vision project developed using Python and OpenCV, designed to perform face detection, face data collection, model training, and real-time face recognition through a webcam.

+ The project applies classical computer vision techniques using the LBPH (Local Binary Patterns Histograms) algorithm for face recognition and Haar Cascade Classifier for face detection.

## 🧰 Technologies Used:

+ Programming Language: Python 3

+ Computer Vision Library: OpenCV (cv2)

+ Algorithm: Haar Cascade (Face Detection), LBPH Face Recognizer (Face Recognition)

+ Libraries: NumPy, PIL (Pillow), OS

+ Hardware: Webcam

## 🎯 Project Objectives

+ Capture and store face images from a webcam

+ Train a face recognition model using LBPH

+ Perform real-time face recognition

+ Display recognized person name and confidence level

+ Build a complete face recognition pipeline

📂 Project Structure
├── dataset/                # Stored face images
├── trainer/                # Trained model files
├── face_dataset.py         # Face data collection script
├── face_training.py        # Model training script
├── face_recognition.py     # Real-time face recognition
└── README.md

## ⚙️ Environment Setup
### ☕ Python Environment

+ Python 3 is required

+ Verify installation:

>                     python --version

## 📦 Required Libraries
>     pip install opencv-python opencv-contrib-python numpy pillow

## ▶ How to Run the Project
- Step 1: Collect Face Data
>                   python face_dataset.py

- Step 2: Train the Model
>                   python face_training.py

- Step 3: Run Real-time Face Recognition
>                   python face_recognition.py
