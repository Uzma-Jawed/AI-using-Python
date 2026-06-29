# 👕 Fashion-MNIST Image Classification using CNN

A deep learning project that classifies clothing images from the Fashion-MNIST dataset using a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras**.

The model is trained on grayscale images of 10 different clothing categories and achieves **90.99% test accuracy** through an improved CNN architecture with Batch Normalization, Dropout, Early Stopping, and Model Checkpointing.

---

## 📌 Project Overview

This project demonstrates the complete workflow of building an image classification model using Deep Learning.

The notebook covers:

* Loading the Fashion-MNIST dataset
* Data preprocessing and normalization
* Building a CNN model
* Training with validation
* Preventing overfitting
* Evaluating model performance
* Visualizing predictions
* Displaying misclassified images

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Dataset

The project uses the **Fashion-MNIST** dataset provided by TensorFlow.

It contains:

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 grayscale
* 10 clothing categories

---

## 🧠 CNN Architecture

The model consists of:

* 3 Convolutional Layers
* Batch Normalization
* Max Pooling
* Flatten Layer
* Dense Hidden Layer (128 neurons)
* Dropout (0.4)
* Softmax Output Layer (10 classes)

Additional training features:

* Adam Optimizer
* Sparse Categorical Crossentropy Loss
* Early Stopping
* Model Checkpoint

---

## 📈 Results

**Test Accuracy:** **90.99%**

The model performs well on most clothing categories.

Some prediction errors occur between visually similar classes such as:

* Shirt
* Coat
* Pullover
* T-shirt/Top

---

## 📊 Visualizations

The notebook includes:

* Sample dataset images
* Training vs Validation Accuracy
* Training vs Validation Loss
* Confusion Matrix
* Classification Report
* Model Predictions
* Misclassified Images

---

## 🚀 How to Run

1. Clone this repository

```bash
git clone https://github.com/Uzma-Jawed/AI-using-Python.git
```

2. Install the required libraries

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn
```

3. Open the notebook

```bash
AiUsingPython_Ex4.ipynb
```

4. Run all cells.

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Image preprocessing
* Building CNNs using TensorFlow/Keras
* Improving model performance with Batch Normalization and Dropout
* Preventing overfitting using Early Stopping
* Evaluating classification models
* Visualizing deep learning results

---

## 👩‍💻 Author

**Uzma Jawed**

Aspiring AI & Data Science Developer

Currently learning Machine Learning, Deep Learning, FastAPI, Streamlit, and Technical Writing while building practical AI projects.

---

⭐ If you found this project useful, consider giving it a star!
