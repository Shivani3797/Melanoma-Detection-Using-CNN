# Melanoma Detection using CNNs in TensorFlow
![Image Description](./image.png)


# Overview
This project aims to develop a multiclass classification model using a custom Convolutional Neural Network (CNN) in TensorFlow to aid in early detection of melanoma, a serious form of skin cancer. Melanoma accounts for a large portion of skin cancer-related deaths, and early detection can significantly improve survival rates. The model evaluates skin lesion images, assisting dermatologists by flagging potential melanoma cases, ultimately supporting faster, more accurate diagnoses.

# Problem Statement
Skin cancer, particularly melanoma, poses severe health risks, accounting for around 75% of skin cancer fatalities. Traditional diagnostic methods are labor-intensive and time-consuming. The project seeks to address this by building a CNN model to detect melanoma in images, reducing the burden on dermatologists and enhancing diagnostic speed and precision.

# Dataset
The dataset includes 2,357 images sourced from the International Skin Imaging Collaboration (ISIC) and spans nine categories of skin conditions:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

# Project Pipeline
## 1. Data Preparation
Define paths for training and testing sets.
Create training and validation datasets with a batch size of 32, resizing images to 180x180 pixels.

## 2. Data Visualization
Visualize samples from each class to understand the distribution and characteristics of the images.

## 3. Model Building & Training
Build a CNN model tailored to accurately identify all nine classes.
Apply normalization to rescale pixel values.
Choose suitable optimizer and loss functions, and train the model for 20 epochs.
Evaluate performance, monitoring for overfitting and underfitting.

## 4. Model Training with Data Augmentation
Implement data augmentation strategies to improve robustness.
Retrain the model on augmented data, assessing improvements after 20 epochs.

## 5. Class Distribution Analysis
Examine the class distribution to identify imbalances.
Address imbalances with the Augmentor library.

## 6. Final Model Training
Rebuild the model using the balanced dataset.
Train for an extended period (up to 30 epochs) to refine accuracy.

# Conclusion
This project demonstrates the use of AI and deep learning in early melanoma detection, potentially supporting medical professionals in making faster, more accurate diagnoses.
