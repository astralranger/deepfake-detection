# Deepfake Detection using MobileNetV2 & Autoencoder

## 🔍 About the Project
Deepfake technology has rapidly evolved, making it crucial to develop robust detection mechanisms. This project implements a **deepfake detection system** using **MobileNetV2** and an **Autoencoder-based anomaly detection model**. The system analyzes both images and videos, providing classification, Grad-CAM visualizations, facial landmarks, and blur detection to enhance interpretability.

## 🎯 Key Features
- **Image & Video Deepfake Detection** – Supports both static images and video frame-by-frame analysis.
- **MobileNetV2 Classifier** – Pretrained MobileNetV2 fine-tuned to detect deepfake images.
- **Autoencoder for Anomaly Detection** – Learns representations of real faces to identify anomalies.
- **Grad-CAM Visualization** – Highlights regions influencing the model's decision.
- **Facial Landmark Detection** – Uses Dlib to map facial features for authenticity checks.
- **Blur Detection** – Identifies artifacts often present in deepfakes.
- **Interactive Web Interface** – Implemented using **Gradio** for user-friendly testing.

## 📂 Dataset
- **Real and Fake Face Dataset** (available at: `https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection`).
- The dataset consists of **real** and **AI-generated fake faces**.
