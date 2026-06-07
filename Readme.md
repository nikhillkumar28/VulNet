# Vulnerability Detection in Network Topology using Computer Vision

## Overview

This project uses YOLOv8 and computer vision techniques to detect physical vulnerabilities in network infrastructure images.

The model identifies:

- Ethernet ports
- Damaged cables
- Unplugged ethernet cables

The system highlights vulnerable areas using bounding boxes and generates warning messages for detected vulnerabilities.

---

## Features

- YOLOv8 Nano based object detection
- Physical vulnerability detection using image processing
- Bounding box visualization
- Detection confidence scores
- Vulnerability warning generation
- Lightweight implementation for college-level AI projects

---

## Classes Detected

| Class | Description |
|------|-------------|
| ethernet_port | Detects ethernet ports |
| damaged_cable | Detects damaged network cables |
| unplugged_cable | Detects unplugged ethernet cables |

---

## Technologies Used

- Python
- YOLOv8
- OpenCV
- NumPy
- Matplotlib
---

## Project Workflow

Input Image  
↓  
YOLOv8 Detection  
↓  
Vulnerability Analysis  
↓  
Annotated Output Image  

---

## Dataset

The dataset was created using publicly available network infrastructure images and manually annotated in YOLO format.

The dataset contains:
- Ethernet port images
- Damaged cable images
- Unplugged cable images

---

## Model Training

The model was trained using:
- YOLOv8 
- Transfer Learning
- Data Augmentation

Training Settings:
- Epochs: 20
- Image Size: 780
- Batch Size: 8

---

## Sample Output

The model detects:
- Damaged cables
- Open port risks
- Physical network infrastructure components

---

## Installation

Install required libraries:

```bash
pip install -r requirements.txt
