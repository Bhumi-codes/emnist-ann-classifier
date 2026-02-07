# EMNIST Character Classification using Artificial Neural Networks (ANN)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Bhumi-codes/emnist-ann-classifier/blob/main/EMNIST.ipynb)

## 📌 Project Overview

This project focuses on training an Artificial Neural Network (ANN) to classify handwritten characters from the **EMNIST** dataset.
EMNIST dataset has a dataset of 1,31,000 rows.
It covers dataset preparation, preprocessing, model training, and performance evaluation.

The primary goal of this project is to build a strong understanding of how neural networks handle image-based multi-class classification problems.

---

## 🚀 Features

* ANN model for handwritten character recognition
* Image preprocessing and normalization
* Training with validation data
* Model performance evaluation
* Trained model saved for future use
* Implemented using TensorFlow / Keras in Google Colab

---

## 🗂 Dataset

**Dataset Used:** EMNIST (Balanced MNIST)

* Grayscale handwritten character images
* Image size: 28 × 28
* Multi-class classification problem

---

## 🧠 Model Architecture

The classifier is built using a fully connected neural network.

General structure:

* Input layer (784 features after flattening)
* Dense hidden layers with activation functions
* Applied regularization in hidden layers
* Output layer with linear activation having model compiled as SparseCategoricalCrossentropy(from_logits=True) that applies
  Softmax during estimating losses for more accurate results.

---

## 📊 Results

* Train and Cross Validation Accuracy : **~86%** and **~83%** respectively.
* Test Accuracy: **~83%**

The model achieves good performance without any issue of underfitting or overfitting
---

## ⚙️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the cells sequentially.
3. The model will train and display evaluation metrics.

---

## 📁 Project Structure

```
├── notebook.ipynb
├── model/
│   └── emnist_ann_classifier.h5
└── README.md
```

---

## 🔮 Future Improvements

* Improve accuracy using CNN-based architectures
* Be able to make proper Pre-Processing pipeline so that it is able to take raw input images as well from the user
* Build an interface for real-time predictions
* Explore deployment options

---


