# CatractDetection
This project focuses on building a deep learning model for the detection of cataracts in ocular images (fundus images). Cataracts are one of the leading causes of blindness worldwide, and early detection is critical for preventing irreversible vision loss. 


# Cataract Detection Using Deep Learning

## Overview
This project aims to detect **cataracts** from **fundus images** using deep learning. Cataracts are one of the leading causes of blindness, and early detection is critical for preventing irreversible vision loss. Traditional detection methods involve manual examination of images, which can be time-consuming and prone to human error. This project leverages Convolutional Neural Networks (CNNs) to automatically classify eye images as **Normal** or **Cataract**, assisting healthcare professionals in quick and accurate diagnosis.

## Dataset
The dataset used for this project is the **ODIR-5K** dataset from Kaggle. The dataset contains **ocular images** labeled into two categories: **Normal** and **Cataract**.

Dataset can be downloaded from Kaggle:
[ODIR-5K Dataset](https://www.kaggle.com/datasets)

## Features
- **Image Classification**: Classify fundus images as either **Normal** or **Cataract**.
- **Data Preprocessing**: Image resizing, normalization, and augmentation.
- **Deep Learning Model**: A CNN-based architecture to classify images.
- **Grad-CAM Visualization**: Visualize the areas of the image the model focuses on for predictions.

## Technologies
- **Python** (v3.7 or above)
- **TensorFlow / Keras**: Deep Learning Framework
- **OpenCV**: Image Processing
- **Matplotlib**: Visualization
- **Grad-CAM**: Explainability tool

## Prerequisites
Make sure you have **Python 3.7+** and the following libraries installed:

- TensorFlow
- Keras
- OpenCV
- Matplotlib
- Numpy
- Scikit-Learn

You can install the required dependencies using:

pip install -r requirements.txt

git clone https://github.com/yourusername/cataract-detection-deep-learning.git
cd cataract-detection-deep-learning

```bash
pip install -r requirements.txt  git clone https://github.com/yourusername/cataract-detection-deep-learning.git
cd cataract-detection-deep-learning

