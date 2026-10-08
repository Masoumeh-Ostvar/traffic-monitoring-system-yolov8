# Traffic Monitoring System with YOLOv8

A computer vision-based traffic monitoring system that utilizes **YOLOv8** for vehicle detection and classification in road surveillance images and videos. The project focuses on building an intelligent traffic analysis pipeline capable of identifying different vehicle categories and evaluating detection performance using standard object detection metrics.

---

## Overview

Traffic monitoring is a fundamental component of intelligent transportation systems, enabling efficient traffic management, road safety assessment, and urban planning.

This project investigates the application of deep learning techniques for automatic vehicle detection and classification. The system is designed to analyze traffic scenes and identify multiple vehicle types under various environmental conditions.

---

## Features

- Vehicle detection using YOLOv8
- Multi-class vehicle classification
- Traffic image and video analysis
- Dataset preprocessing and augmentation
- Performance evaluation using industry-standard metrics
- Support for real-world traffic datasets
- Comparative analysis of detection performance under different conditions

---

## Vehicle Categories

The system can be trained to recognize vehicle categories such as:

- Car
- Bus
- Truck
- Motorcycle
- Van

> **Note:** The final classes depend on the selected dataset and training configuration.

---

## Methodology

```text
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Dataset Annotation & Formatting
        │
        ▼
YOLOv8 Training
        │
        ▼
Vehicle Detection
        │
        ▼
Vehicle Classification
        │
        ▼
Performance Evaluation
```

---

## Dataset

The project utilizes publicly available vehicle datasets, including:

- [Cars Image Dataset](https://www.kaggle.com/datasets/kshitij192/cars-image-dataset) (Kaggle)
- [Iran Vehicle Plate Dataset](https://www.kaggle.com/datasets/samyarr/iranvehicleplatedataset) (Kaggle)
- Additional traffic datasets from Roboflow and similar sources

The dataset is divided into training, validation, and test sets to ensure reliable model evaluation.

---

## Data Preprocessing

The project investigates preprocessing techniques to improve model robustness under challenging environmental conditions, including:

- Contrast enhancement
- Denoising
- Brightness correction
- Image sharpening
- Dehazing

The impact of preprocessing is evaluated experimentally using standard object detection metrics.

---

## Evaluation Metrics

Model performance is evaluated using standard object detection metrics:

- Precision
- Recall
- F1-Score
- Average Precision (AP)
- Mean Average Precision (mAP)
- Precision-Recall Curve

These metrics provide a comprehensive assessment of detection accuracy and robustness.

---

## Technologies

- Python
- YOLOv8
- Ultralytics
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## Objectives

- Develop a deep learning-based vehicle detection system
- Classify vehicles into multiple categories
- Explore dataset preprocessing techniques
- Evaluate model performance using standard metrics
- Analyze the applicability of YOLOv8 for traffic monitoring tasks

---

## Future Improvements

- Multi-object tracking
- Real-time vehicle counting
- Vehicle speed estimation
- Traffic density analysis
- License plate recognition
- Deployment on edge devices

---

## Documentation

A detailed project report containing system design, implementation details, experimental setup, and evaluation results is available in:

[📄 View Project Report](Report.pdf)

---

## Project Goal

The primary goal of this project is to investigate the effectiveness of **YOLOv8** for intelligent traffic monitoring and vehicle analysis tasks, while exploring preprocessing strategies that improve detection performance in real-world scenarios.
