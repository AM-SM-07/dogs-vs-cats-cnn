# 🐶🐱 Dogs vs Cats Image Classification using CNN

An end-to-end Computer Vision project for classifying images
as either Dog or Cat using a Convolutional Neural Network.

## 📌 Project Overview

This project uses the Kaggle Dogs vs. Cats Redux: Kernels Edition dataset containing
25,000 labeled training images.

The objective is to build a CNN-based binary image
classification pipeline capable of distinguishing between
cats and dogs.

## 📊 Dataset

Dataset: Kaggle Dogs vs. Cats Redux: Kernels Edition

Training Images: 25,000

The raw dataset is not included in this repository.

## 🧠 Model

The CNN consists of:

- Convolutional layers
- Max Pooling layers
- Fully Connected layer
- Dropout
- Softmax output layer

## ⚙️ Preprocessing

- Images converted to grayscale
- Images resized to 50 × 50
- Labels converted to one-hot encoding
- Training and validation data prepared for CNN input

## 🛠️ Technologies

- Python
- TensorFlow
- TFLearn
- OpenCV
- NumPy
- Matplotlib

## 📈 Workflow

Dataset
→ Preprocessing
→ CNN
→ Training
→ Validation
→ Prediction

## 🧪 Results

The trained model was used to generate predictions
for unseen test images.

Sample predictions:

![Predictions](results/sample_predictions.png)

## 📦 Kaggle Submission

A submission file was generated for the Kaggle Dogs vs Cats
competition.

The competition is no longer accepting late submissions,
so no Kaggle leaderboard score is claimed.

## 🚀 Future Improvements

- Data augmentation
- RGB image processing
- Transfer learning
- Batch normalization
- Hyperparameter tuning
- Improved evaluation metrics
- Deployment as a web application
