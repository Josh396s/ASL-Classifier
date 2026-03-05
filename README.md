# ASL Gesture Recognition via Deep Learning

This repository implements a Convolutional Neural Network (CNN) to classify American Sign Language (ASL) alphabetical gestures. It focuses on optimizing a custom architecture for high accuracy and minimal overfitting. It also explores Transfer Learning using VGG16 model.

## Features
- **Custom CNN Design**: Utilizes strided convolutions and max-pooling for spatial feature extraction.
- **Regularization**: Incorporates `Dropout` and `RandomRotation` layers to improve model robustness on unseen data.
- **Data Pipeline**: Implements an efficient TensorFlow input pipeline with auto-normalization.

## Getting Started
1. Install dependencies: `pip install tensorflow matplotlib`
2. Download the ASL Alphabet dataset (1000 samples per class) and place it in `asl_1000/`.
3. Run the notebook for a detailed analysis or use the script to integrate the model.
