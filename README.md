# Face Mask Detection using TensorFlow

## Overview
This project aims to detect whether a person is wearing a face mask or not using deep learning with TensorFlow and Keras. The model is trained on images of people with and without face masks and can be deployed for real-time face mask detection.

## Features
- Detects face masks in images and video streams
- Uses TensorFlow and Keras for deep learning
- Trained on a dataset of masked and unmasked faces
- Can be deployed on real-time applications using OpenCV

## Dataset
The dataset consists of:
- Images of people **wearing masks**
- Images of people **not wearing masks**

Preprocessing includes:
- Resizing images to a fixed size
- Data augmentation to improve generalization

## Model Architecture
- Uses **Convolutional Neural Networks (CNNs)**
- Implemented with TensorFlow and Keras
- Includes dropout layers to reduce overfitting

## Performance Metrics
The model is evaluated using:
- **Accuracy**
- **Precision & Recall**
- **Confusion Matrix**

## Future Improvements
- Improve accuracy with more training data
- Optimize model for mobile and edge devices
- Deploy as a web-based application

