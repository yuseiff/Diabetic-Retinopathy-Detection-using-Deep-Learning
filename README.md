# Diabetic Retinopathy Detection using Deep Learning

## Overview
This project aims to develop a deep learning model for the detection of diabetic retinopathy from retinal images. By leveraging TensorFlow and Keras, the model will classify images into different categories, helping in early diagnosis and treatment.

![dataset-cover](https://github.com/user-attachments/assets/31974527-5fa3-413f-813d-507857fee6ed)


## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Data](#data)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## Introduction
Diabetic retinopathy is a complication of diabetes that affects the eyes. Early detection is crucial for effective treatment. This project employs convolutional neural networks (CNNs) to automatically classify retinal images, making it easier for healthcare professionals to diagnose the condition.

## Requirements
- Python 3.10
- TensorFlow 2.10.1
- Keras 2.10.0
- OpenCV 4.10.0.84
- NumPy 1.26.4
- Pandas 2.2.2
- Matplotlib 3.9.0
- scikit-learn 1.5.0
- imbalanced-learn 0.12.3
- tqdm 4.66.4

## Data
The dataset used in this project is obtained from Kaggle and consists of retinal images categorized into different classes based on the severity of diabetic retinopathy.

1. With DR
![With DR](https://github.com/user-attachments/assets/1ce8a10b-5dad-4efb-a856-5c53eb9014d5)

2. Without DR
![Without DR](https://github.com/user-attachments/assets/260ebe93-a645-4d22-bdda-a1a687572d54)

## Model Training
The model is trained using the training dataset.

## Results
The performance of the model will be evaluated using metrics such as accuracy, precision, recall, and F1-score. Visualizations of the results will be provided in the notebook.

## Acknowledgments
[Kaggle](https://www.kaggle.com/datasets/pkdarabi/diagnosis-of-diabetic-retinopathy) for providing the dataset.
TensorFlow and Keras for the deep learning framework.
The open-source community for valuable resources and libraries.
