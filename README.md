# AI-Based Facial Micro-Expression Recognition System Using Machine Learning and Deep Learning

## Overview

NeuroVision is an AI-based facial micro-expression recognition system developed to recognize subtle and brief facial expressions using computer vision, machine learning, and deep learning techniques.

The system explores both traditional machine learning and deep learning approaches for facial micro-expression recognition and provides an application interface for demonstrating the trained recognition model.

## Project Objectives

- Develop a system for recognizing facial micro-expressions.
- Apply computer vision techniques for facial image preprocessing.
- Extract meaningful features from facial data.
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
```markdown
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
Deep Learning

The deep learning approach uses the SMIC dataset and a Convolutional Neural Network (CNN) for facial micro-expression recognition.

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

### Look at what is happening

The first diagram starts with:

```text
```text
Input Frames
...
Micro-Expression Recognition

**That second ` ``` ` is what closes the code block.**

Then we have:

```text
### Deep Learning

Because the previous code block has been closed, GitHub understands that this is a heading, so it will appear normally.

Then the second diagram starts:

```text
Input Facial Image
...
Micro-Expression Recognition

Again, we close it at the end.

---

### What you should do right now

Since your README is already partially entered, **don't try to fix the entire thing manually**.

Go to your `README.md` → **Edit**.

Find this part:

> `### Traditional Machine Learning`

and replace everything from **`## Methodology` through the end of the Deep Learning diagram** with the corrected section above.

Then click **Preview**.

You should see:

**Methodology**

The project consists...

### Traditional Machine Learning

The traditional machine learning pipeline...

**Input Frames**  
↓  
**Face Detection**  
↓  
...

### Deep Learning

The deep learning approach...

**Input Facial Image**  
↓  
**Preprocessing**  
↓  
...

Everything after **Deep Learning** should now be normal, bright text again. 👍

**Don't worry about the rest of the README yet.** Let's get this formatting working first, then I'll help you with the remaining sections o
