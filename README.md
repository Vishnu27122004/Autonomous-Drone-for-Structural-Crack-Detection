# 🚁 Autonomous Drone for Structural Crack Detection

A drone-based system developed to **autonomously detect structural cracks** in bridges, buildings, and other infrastructures using **computer vision** and **machine learning**. Equipped with high-resolution cameras and thermal sensors, the drone captures images of hard-to-reach areas and processes them using **OpenCV** and **Python** for accurate crack detection.

## 🧩 Key Features
- Real-time image capture via IP camera or onboard module
- Crack detection using edge detection and contour analysis in OpenCV
- Autonomous navigation with GPS + RTK modules
- Integration of thermal sensors and LiDAR for enhanced accuracy
- Automated report generation with inspection visuals and metrics

## 🛠️ Tech Stack
- **Drone Hardware**: Omnibus F4 V2 Pro, ESC, Brushless Motors, LiPo Battery
- **Sensors**: CMOS Camera, Thermal Camera, LiDAR, Ultrasonic
- **Programming**: Python, OpenCV, C++
- **Flight Control**: ArduPilot / PX4
- **Machine Learning**: TensorFlow (for CNN crack classification)
- **Visualization & Reporting**: Web dashboard, optional Power BI

## 📷 System Architecture
![Drone Setup](images/drone_setup.jpg)

## 💻 Code Usage
- Run `image_processing/crack_detection.py` to start crack detection using a webcam or IP camera.
- Trained CNN model file: `models/cnn_model.h5` (if included)
- Requirements: `pip install -r requirements.txt`

> 👨‍🔧 Developed by a 10-member interdisciplinary team from Aeronautical, ECE, and CS departments. 
# Autonomous-Drone-for-Structural-Crack-Detection
