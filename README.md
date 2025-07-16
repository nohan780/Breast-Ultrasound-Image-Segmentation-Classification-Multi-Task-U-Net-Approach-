# Breast-Ultrasound-Image-Segmentation-Classification-Multi-Task-U-Net-Approach-

## 🎯 Multi-Task U-Net Approach

This project implements a **Multi-Task U-Net model** for simultaneous **segmentation and classification** of breast ultrasound images. The goal is to assist in early breast cancer detection by identifying tumor regions and classifying them as benign or malignant or normal using deep learning.

## 🔍 Overview

- **Dataset**: Breast Ultrasound Images Dataset (BUID)
- **Model**: Multi-task U-Net combining:
  - **Segmentation head** for tumor region detection
  - **Classification head** for benign vs. malignant vs. normal prediction
- **Framework**: TensorFlow / Keras
- **Output**: Segmentation masks + class labels per image
