# Real-Time Face Mask Detection using Deep Learning
A real-time computer vision system that detects whether a person is wearing a face mask using deep learning and OpenCV.

## Overview

This project implements a real-time face mask detection system using deep learning and computer vision techniques.  
The system detects human faces from live video streams and classifies each face as **Mask** or **No Mask** with confidence scores.

The primary focus of this project is practical deployment, real-time inference performance, and clean system design rather than only model accuracy.

## Key Features

- Real-time face detection from webcam or video streams  
- Deep learning–based face mask classification  
- Bounding boxes with class labels and confidence scores  
- Lightweight CNN model optimized for speed  
- Modular and readable code structure

## Tech Stack

- Python  
- OpenCV  
- TensorFlow / Keras  
- NumPy  
- Scikit-learn

## Project Structure

```text
real-time-face-mask-detection/
│
├── data/               # Dataset (not included in repository)
├── model/              # Trained model files
├── results/            # Output images / demo GIFs
│
├── train.py            # Model training script
├── detect.py           # Real-time mask detection
├── utils.py            # Helper functions
├── requirements.txt    # Project dependencies
└── README.md
