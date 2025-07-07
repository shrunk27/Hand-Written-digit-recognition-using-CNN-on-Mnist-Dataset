# 🧠 Handwritten Digit Recognition using CNN (MNIST Dataset)

This project demonstrates a Convolutional Neural Network (CNN) model built using TensorFlow/Keras to recognize handwritten digits from the MNIST dataset.

---

## 📌 Overview

- **Goal**: Classify digits (0 to 9) from handwritten images.
- **Dataset**: [MNIST](http://yann.lecun.com/exdb/mnist/) – 70,000 grayscale images (28x28).
- **Model**: CNN with 2 convolutional layers, pooling, dropout, and dense output layer.
- **Accuracy**: Achieved ~98% test accuracy.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib (for visualization)

---

## 📁 Dataset

The MNIST dataset is automatically downloaded via:
```python
from tensorflow.keras.datasets import mnist

** Model Architechture:**
Input: (28, 28, 1)
↓
Conv2D(32) + ReLU
↓
MaxPooling2D
↓
Conv2D(64) + ReLU
↓
MaxPooling2D
↓
Flatten
↓
Dense(128) + ReLU
↓
Dropout(0.5)
↓
Dense(10) + Softmax
