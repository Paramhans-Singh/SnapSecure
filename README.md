
# 🚗 SnapSecure: Real-time ANPR System with Face Detection 🕵️‍♂️

## Overview 📋

**SnapSecure** is an advanced real-time Automatic Number Plate Recognition (ANPR) system with integrated face detection capabilities. This project combines state-of-the-art machine learning models to ensure accurate detection and high-speed processing, making it ideal for security and surveillance applications.

## Features ✨

- **Dual Detection System:** Combines YOLO V5 for high-precision object detection with Haar Cascades for accurate and efficient face detection.
- **Real-time Performance:** ⚡ Optimized using OpenCV for instant processing of video streams.
- **Scalability:** 📈 Designed to handle high-traffic scenarios, making it suitable for deployment in various environments.


## Tools & Technologies 🛠️

- **Flask:** 🌐 Web framework for building the application's backend.
- **OpenCV:** 📸 Library used for image processing and real-time computer vision tasks.
- **OCR (Optical Character Recognition):** 🔍 Integrated to extract text from detected license plates.
- **FaceNet:** 🤖 Utilized for robust face recognition.
- **dlib:** 📏 Library for facial landmark detection and other machine learning tasks.
- **Tensorflow:** 🧠 Framework for training and deploying machine learning models.
- **YOLO V5:** 🎯 Model used for object detection, particularly for identifying vehicles and number plates.

## How It Works ⚙️

### 1. Video Stream Processing 🎞️
The system captures video streams and processes each frame to detect vehicles and faces using YOLO V5 and Haar Cascades.

### 2. License Plate Recognition 🆔
Once a vehicle is detected, the ANPR system extracts the license plate area, which is then passed through an OCR engine to recognize the text.

### 3. Face Detection 👀
Simultaneously, the system identifies faces within the same video stream using FaceNet and dlib, providing an additional layer of security.

### 4. Real-time Analysis 🕒
The processed data is analyzed in real-time, with results displayed instantly, ensuring minimal latency.

## Installation 🛠️

To get started with SnapSecure, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/SnapSecure.git
   cd SnapSecure
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application:**
   ```bash
   python app.py
   ```

4. **Access the Application:**
   Open your browser and navigate to `http://localhost:5000`.

## Contributing 🤝

Contributions are welcome! Please feel free to submit a Pull Request.
