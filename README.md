# 🩸 Blood Group Detection Using Fingerprint

This project aims to detect the **blood group** of a person using their **fingerprint image** with the help of a deep learning model and a web-based interface built using Flask.

## 🚀 Project Overview

Traditional blood group detection methods require biochemical analysis. This project explores an innovative, non-invasive approach using fingerprint patterns. A convolutional neural network (EfficientNet) is trained on fingerprint images labeled with blood groups, and deployed through a simple web interface.

## 🧠 Model Summary

- **Model Used:** EfficientNet (Keras)
- **Input Size:** 224x224 RGB images
- **Classes:** A+, A−, AB+, AB−, B+, B−, O+, O−
- **Training Data:** Grayscale fingerprint images converted to RGB
- **Preprocessing:** Standard EfficientNet preprocessing
- **Output:** Predicted blood group and confidence score

## 🖥️ App Features

- Upload fingerprint image in JPG, PNG, BMP, or JPEG format
- View predicted blood group and confidence
- Lightweight Flask app with simple UI
