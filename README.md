
Handwritten Digit Recognizer
Overview
This project builds a machine learning model to classify handwritten digits using the MNIST dataset. It demonstrates the implementation of Logistic Regression and Convolutional Neural Networks (CNNs) for digit recognition.

Applications
Optical Character Recognition (OCR)
Check verification and form digitization
Handwriting recognition for postal codes
Educational tools for handwriting analysis
Dataset
Training Set: 60,000 images
Testing Set: 10,000 images
Dataset Link
Models and Performance
Model	Accuracy (%)	Remarks
Logistic Regression	91.5	Baseline model
CNN	98.9	Best performance, robust to variations
Key Features
Preprocessing:
Normalization of pixel values to [0, 1]
Reshaping images for fully connected or convolutional layers
Train-test split and one-hot encoding of labels
Best Model:
CNN, achieving 98.9% accuracy by capturing spatial patterns like edges and shapes
Future Work
Extend to other numeral systems (e.g., Devanagari, Arabic)
Improve robustness for noisy or distorted images
Deploy as a web or mobile app for real-time digit recognition
