As part of an initiative for International Dance Day, we were tasked with classifying images into eight Indian classical dance forms:
Manipuri, Bharatanatyam, Odissi, Kathakali, Kathak, Sattriya, Kuchipudi, and Mohiniyattam.

Given a limited dataset (364 training images), we applied Transfer Learning using the VGG16 model from TensorFlow, pre-trained on ImageNet. This approach helps in extracting rich features from images and improves model performance even with smaller datasets.

Steps followed:

Loaded and preprocessed image data from the train folder.

Used the VGG16 model (excluding top layers) to extract features.

Added custom dense layers for classification.

Trained the model using the labeled data from train.csv.

Generated predictions for test images and saved them in the required submission format.

This approach efficiently classifies classical dance images and demonstrates the power of Transfer Learning for real-world image classification tasks with limited data.

