# Media-Gesture-Control
A computer vision project using Pytorch , YOLOv8 and MediaPipe for real-time hand gesture recognition to control Media Player.

# 🎯 Gesture-Based Media Player Controller

This project enables users to control **VLC Media Player** using **hand gestures** in real-time. It integrates **YOLOv8** (for hand detection) and **MediaPipe** (for precise hand tracking), with **PyTorch optimizations** for improved performance.

---

## 🚀 How It Works
- **YOLOv8 (Ultralytics)** detects hands in the video stream.
- **MediaPipe** extracts hand landmarks to analyze finger positions.
- Gestures are classified based on landmark positions.
- **PyTorch optimizations** enhance real-time processing.
- **PyAutoGUI** sends keyboard shortcuts to VLC based on detected gestures.

---

## 🌟 Features
✅ Real-time hand gesture recognition  
✅ No need for a keyboard or mouse  
✅ Accurate hand tracking using YOLOv8 and MediaPipe  
✅ Works with a standard webcam  
✅ Optimized using PyTorch  

---

## 🛠 Tech Stack
- **OpenCV** - Real-time video processing
- **YOLOv8 (Ultralytics)** - Fast hand detection
- **MediaPipe** - Hand landmark tracking
- **PyTorch** - Model optimization
- **PyAutoGUI** - Sends keyboard commands to VLC

---

## 📌 Installation

Run the following command to install the required dependencies:

```bash
pip install opencv-python mediapipe torch torchvision ultralytics pyautogui
