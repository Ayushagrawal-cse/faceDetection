Face, Eye & Smile Detection using OpenCV

A real-time computer vision application that detects faces, eyes, and smiles using Haar Cascade Classifiers in OpenCV.
This project demonstrates practical implementation of object detection techniques and real-time video processing using Python.

📌 Project Overview

This application captures live video from a webcam and performs hierarchical detection:
Detects human faces in real-time
Detects eyes within detected face regions
Detects smiles within detected face regions
Draws bounding boxes around detected features
The project highlights understanding of:
Classical computer vision techniques
Haar Cascade-based object detection
Region of Interest (ROI) optimization
Real-time frame processing

🛠️ Tech Stack-

Language: Python 3
Library: OpenCV
Model Type: Haar Cascade Classifiers
Environment: Local webcam-based execution


🧠 Implementation Details

Used pre-trained Haar cascade XML classifiers:
haarcascade_frontalface_default.xml
haarcascade_eye.xml
haarcascade_smile.xml
Converted frames to grayscale for improved detection accuracy.
Applied multi-scale detection using detectMultiScale().
Restricted eye and smile detection within face ROI to improve performance and reduce false positives.
Implemented real-time bounding box visualization.


📈 Key Learning Outcomes

Practical exposure to real-time computer vision pipelines
Understanding of classical ML-based object detection methods
Performance optimization using Region of Interest (ROI)
Handling webcam video streams in OpenCV


🚀 Future Improvements

To extend this project further:
Replace Haar Cascades with Deep Learning models (DNN / CNN-based detectors) for improved accuracy
Integrate MediaPipe Face Mesh for facial landmark detection
Add emotion detection using a trained CNN model
Implement face recognition using LBPH or deep learning embeddings
Deploy as a web application using Flask / Streamlit
Containerize using Docker
Add logging and performance benchmarking
Create a GUI-based version (Tkinter or PyQt)
Optimize for low-light and partial occlusion scenarios



