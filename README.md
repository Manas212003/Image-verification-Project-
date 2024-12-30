 Image Classification App

This project implements an image classification application using two different models:
1. MobileNetV2 (ImageNet) for general image classification.
2. Custom CIFAR-10 model for classifying images into 10 categories from the CIFAR-10 dataset.

Project Structure
- Implementation-of-ML-model-for-image-classification.ipynb: Jupyter notebook for training, evaluating, and saving the CIFAR-10 model.
- model111.h5: Pre-trained CIFAR-10 model saved in HDF5 format.
- newApp.py: Streamlit application for running image classification using the two models.

Features
1. MobileNetV2 (ImageNet) Classification:
   - Supports .jpg and .png images.
   - Classifies the uploaded image into one of 1,000 classes from the ImageNet dataset.
   - Outputs the top class with its confidence score.

2. CIFAR-10 Classification:
   - Supports .jpg and .png images.
   - Classifies the uploaded image into one of 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
   - Outputs the predicted class with its confidence score.

Requirements
- Python 3.7 or later
- Required libraries: 
  - streamlit
  - numpy
  - tensorflow
  - Pillow

Install the dependencies using: bash
pip install -r requirements.txt
