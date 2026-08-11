# AI-Based Facial Micro-Expression Recognition System Using Machine Learning and Deep Learning

## Overview

NeuroVision is an AI-based facial micro-expression recognition system developed to recognize subtle and brief facial expressions using computer vision, machine learning, and deep learning techniques.

The system explores both traditional machine learning and deep learning approaches for facial micro-expression recognition. It also provides an interactive application interface for demonstrating the trained recognition model.

## Project Objectives

- Develop a system for recognizing facial micro-expressions.
- Apply computer vision techniques for facial image preprocessing.
- Extract meaningful spatial and temporal features from facial data.
- Evaluate traditional machine learning and deep learning approaches.
- Develop a convolutional neural network for facial micro-expression recognition.
- Provide an interactive interface for demonstrating the trained model.

## Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- scikit-learn
- TensorFlow
- Keras
- Mahotas
- Streamlit
- Haar Cascade
- MediaPipe

## Methodology

The project consists of two major approaches: traditional machine learning and deep learning.

### Traditional Machine Learning

The traditional machine learning pipeline uses the CASME II dataset and follows a feature-based recognition approach.

```text
Input Frames
     ↓
Face Detection
     ↓
Face Cropping & Resizing
     ↓
Normalization
     ↓
LBP-TOP Feature Extraction
     ↓
SVM Classification
     ↓
Micro-Expression Recognition
```

### Deep Learning

The deep learning approach uses the SMIC dataset and a Convolutional Neural Network (CNN) for facial micro-expression recognition.

```text
Input Facial Image
        ↓
Preprocessing
        ↓
Grayscale Conversion
        ↓
Image Resizing
        ↓
Convolutional Neural Network
        ↓
Feature Learning
        ↓
Classification
        ↓
Micro-Expression Recognition
```

## Datasets

The project uses publicly available facial micro-expression datasets for experimentation.

### CASME II

CASME II is used for the traditional machine learning pipeline involving preprocessing, LBP-TOP feature extraction, and Support Vector Machine classification.

### SMIC

SMIC is used for the deep learning pipeline involving preprocessing and Convolutional Neural Network-based classification.

Dataset files are not included in this repository.

## Machine Learning Approach

The traditional machine learning pipeline uses Local Binary Pattern on Three Orthogonal Planes (LBP-TOP) for spatiotemporal feature extraction.

The extracted features are used to train a Support Vector Machine (SVM) classifier for facial micro-expression recognition.

The pipeline includes face detection, face cropping, image resizing, normalization, LBP-TOP feature extraction, feature standardization, and classification.

## Deep Learning Approach

The deep learning pipeline uses a Convolutional Neural Network (CNN) to automatically learn relevant visual features from facial images.

The CNN architecture includes convolutional layers, pooling layers, dropout, flattening, and fully connected classification layers.

The trained CNN model is used for facial micro-expression recognition and is integrated into the application's prediction pipeline.

## Application

A Streamlit-based application is used to demonstrate the trained deep learning model.

The application provides an interactive interface through which facial input can be supplied to the recognition system and the predicted micro-expression category can be displayed.

## Project Structure

The repository is organized to separate source code, trained models, notebooks, and supporting resources.

```text
neurovision/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
├── models/
├── notebooks/
└── screenshots/
```

The exact structure may vary depending on the implementation modules included in the repository.

## Results

The project evaluates both traditional machine learning and deep learning approaches for facial micro-expression recognition.

Performance depends on factors including the dataset, preprocessing pipeline, feature representation, model architecture, and evaluation methodology.

Detailed experimental results will be documented alongside the relevant implementation and evaluation components.

## Future Improvements

- Improve recognition performance on unseen datasets.
- Increase robustness against variations in lighting, pose, and image quality.
- Explore advanced deep learning architectures.
- Improve temporal modeling of facial micro-expressions.
- Expand the range of recognizable micro-expression categories.
- Improve real-time recognition capabilities.
- Evaluate the system on additional facial micro-expression datasets.

## Academic Project

NeuroVision was developed as a Final Year Project in the field of Computer Science, combining computer vision, machine learning, and deep learning techniques for facial micro-expression recognition.

The project demonstrates the application of both traditional feature-based machine learning and deep learning approaches to the recognition of subtle facial expressions.
