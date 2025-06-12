# 🛣️ Deep Learning-Based Lane Detection for Autonomous Driving

A deep learning project focused on detecting car lane boundaries in real-time from video input, trained on the **CurveLanes** dataset. The system uses convolutional neural networks for robust detection of both straight and curved lanes, contributing to the perception stack of autonomous vehicles.

---

## 🎯 Project Overview

The goal of this project is to create a computer vision system that identifies and highlights road lane lines using deep learning techniques. It processes each video frame and overlays detected lanes, supporting real-time operation and adaptability to different road conditions.

---

## 🧠 Key Components

- **Dataset**: CurveLanes – annotated lane markings with complex road shapes.
- **Model**: CNN-based architecture for segmentation and lane fitting.
- **Input**: Video or single image frames
- **Output**: Lane boundaries highlighted on the original frame

---

## 🛠️ Tech Stack

- **Programming Language:** Python 3.x  
- **Frameworks & Libraries:** PyTorch, OpenCV, NumPy, Matplotlib

---

## 🔍 Features

- Real-time lane line detection (video and frame-level)
- Handles curved, faded, and dashed lanes
- Custom data loader and preprocessing pipeline for CurveLanes
- Visualization of output with overlaid lane masks
- Frame-by-frame annotation and post-processing

---

## 🚀 Getting Started

1. **Clone the repository**  
```bash
git clone https://github.com/Mayonaisey/lane-detection-ai.git
cd lane-detection-ai
