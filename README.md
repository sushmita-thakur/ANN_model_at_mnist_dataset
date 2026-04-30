# 🔢 MNIST Handwritten Digit Recognition using ANN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview
This project implements an **Artificial Neural Network (ANN)** to classify handwritten digits (0-9) from the famous **MNIST dataset**. The goal was to achieve high accuracy while maintaining a simple and efficient architecture.

### Key Highlights:
* **Accuracy:** Achieved ~97.5% on the validation set.
* **Optimization:** Used Adam optimizer with Sparse Categorical Crossentropy.
* **Regularization:** Implemented Dropout layers to prevent overfitting.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Library:** TensorFlow / Keras
* **Data Manipulation:** NumPy
* **Visualization:** Matplotlib

---

## 🏗️ Model Architecture
The model consists of a simple yet powerful sequential structure:
1. **Flatten Layer:** Converts 28x28 images into a 1-D vector of 784 pixels.
2. **Dense Layer (Hidden):** 128 neurons with **ReLU** activation.
3. **Dropout Layer:** 20% dropout to ensure better generalization.
4. **Dense Layer (Output):** 10 neurons with **Softmax** activation for multi-class classification.

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone <your-repo-link>