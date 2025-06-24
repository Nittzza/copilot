# Face and Voice Recognition System

A Python-based biometric authentication system that verifies users based on both facial features and voice characteristics, enhancing identity validation through a multi-modal approach.

## 🔍 Overview

This project integrates facial recognition and voice recognition to create a more secure and reliable user authentication system. It captures and processes real-time input from a webcam and microphone, using machine learning models to detect, identify, and verify individuals.

## ⚙️ Features

- 🎥 **Real-time Face Detection & Recognition** using OpenCV and LBPH algorithm  
- 🎤 **Voice Recognition** using MFCC features and a classification model  
- 🔐 **Multi-factor Biometric Authentication**  
- 🧠 Simple and customizable model training pipeline for new users  
- 🗂️ Local storage and retrieval of face and voice data for verification

## 🛠️ Tech Stack

- **Language**: Python  
- **Libraries**: OpenCV, NumPy, SciPy, SpeechRecognition, librosa, scikit-learn  
- **Model**: LBPH for face recognition, SVM/KNN for voice classification  
- **Tools**: Jupyter/Thonny/VS Code, Webcam, Microphone

## 🚀 How to Run
 Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-voice-auth.git
   cd face-voice-auth

