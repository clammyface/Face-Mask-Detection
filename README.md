Face Mask Detection

Overview

This project is a deep learning-based face mask detection system that identifies whether a person is wearing a face mask or not. The model is trained using TensorFlow and OpenCV for real-time mask detection.

Features

Detects faces with and without masks in real-time.

Uses OpenCV for face detection and image preprocessing.

Trained using Convolutional Neural Networks (CNNs) in TensorFlow/Keras.

Supports both static image detection and live webcam feed.

Evaluates model performance using accuracy, precision, and recall metrics.

Installation

Clone the repository:

Install dependencies:

Run the detection script:

Dataset

The model is trained using a dataset consisting of labeled images with and without face masks.

Data preprocessing includes resizing, normalization, and augmentation.

Model Training

The CNN model is trained on the dataset with categorical cross-entropy loss.

Optimized using Adam optimizer and trained with real-time image augmentation.

Achieves high accuracy in distinguishing between masked and unmasked faces.

Usage

To test on images, place test images in the test_images/ folder and run:

To run real-time detection using a webcam:

Results

Achieved an accuracy of XX% on the validation set.

Real-time inference speed optimized for deployment.
