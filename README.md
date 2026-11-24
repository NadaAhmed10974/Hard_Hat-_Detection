Hard Hat Detection System | Computer Vision

Project Overview

A Computer Vision project that uses YOLOv8 Object Detection to detect safety helmets, heads, and people in construction environments.

The goal is to support workplace safety monitoring by identifying detected objects in images and videos.

Problem Statement

Construction workers may face safety risks when working without proper protective equipment. This project explores how Computer Vision can help detect safety helmets and support safety monitoring.

Technologies Used

- Python
- Computer Vision
- YOLOv8 (Ultralytics)
- OpenCV
- PyTorch
- Google Colab
- NumPy
- Matplotlib

Dataset

Dataset: Hard Hat Workers
Dataset Source

The dataset used in this project is Hard Hat Workers, provided by Northeastern University – China through Roboflow Universe.

- Source: "Roboflow – Hard Hat Workers" (https://universe.roboflow.com/joseph-nelson/hard-hat-workers)
- Task: Object Detection
- Classes: Head, Helmet, Person
- License: Public Domain
- Dataset Format: YOLO

The dataset was downloaded from Roboflow and used for training and evaluation.

The dataset files are not included in this repository. Please visit the original source to access and download the dataset.

Classes:

- Head
- Helmet
- Person

The dataset is provided in YOLO format with images and bounding-box annotations.

Dataset files are not included in this repository because of their size.

Model

YOLOv8n (Nano) pretrained model using Transfer Learning.

Project Features

- Dataset preparation and inspection
- Image visualization with bounding boxes
- YOLOv8 model training
- Model evaluation
- Object detection on images
- Object detection on videos
- Basic safety alert prototype

How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Select a GPU runtime.
3. Upload the dataset ZIP file when requested.
4. Run the notebook cells in order.
5. Train and evaluate the model.
6. Test object detection on images and videos.

Evaluation Metrics

The model is evaluated using:

- Precision
- Recall
- mAP@50
- mAP@50-95

 ## Model Results

### Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

### Training Results
![Training Results](results/results.png)

### Validation Predictions
![Validation Predictions](results/val_batch0_pred.jpg)
Future Improvements

- Improve detection of underrepresented classes.
- Improve person-to-helmet association.
- Test the system on more real-world videos.
- Develop a more reliable real-time safety monitoring system.

Limitations

This project is an educational prototype. Object detection alone does not guarantee accurate person-level helmet compliance decisions.

Author

Nada Ahmed

Computer Science Student | Artificial Intelligence

Machine Learning | Deep Learning | Computer Vision# Hard_Hat-_Detection
Computer Vision Project using YOLOv8
