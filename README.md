# MNIST Image Classifier using CNN

A simple **Convolutional Neural Network (CNN)** based image classification project built with **TensorFlow 2.20** and **Keras 3**. This project trains a deep learning model to recognize handwritten digits (0–9) from the **MNIST dataset**.

---

## 📌 Project Overview

The goal of this project is to demonstrate how a CNN can be used to classify grayscale images using deep learning. The model is trained on the MNIST dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits.

This project is ideal for:

* Beginners learning **Deep Learning**
* Students exploring **CNN architectures**
* Developers practicing **TensorFlow & Keras**

---

## 🧠 Model Architecture

The CNN architecture consists of:

* Input Layer: 28×28 grayscale images
* Convolutional Layer (32 filters, 3×3, ReLU)
* Max Pooling Layer (2×2)
* Convolutional Layer (64 filters, 3×3, ReLU)
* Max Pooling Layer (2×2)
* Convolutional Layer (64 filters, 3×3, ReLU)
* Flatten Layer
* Fully Connected Dense Layer (64 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

---

## 🗂️ Dataset

**MNIST Handwritten Digits Dataset**

* Image Size: 28×28 pixels
* Color Format: Grayscale
* Classes: Digits from 0 to 9
* Training Samples: 60,000
* Test Samples: 10,000

The dataset is automatically downloaded using Keras.

---

## ⚙️ Technologies Used

* Python 3.10+
* TensorFlow 2.20
* Keras 3
* NumPy
* Pillow

---

## 📦 Installation

1. **Clone the repository**

```bash
git clone <your-repo-url>
cd image_classifier
```

2. **Create a virtual environment**

```bash
python -m venv .venv
```

3. **Activate the virtual environment**

* Windows (PowerShell):

```bash
.venv\Scripts\Activate.ps1
```

* macOS / Linux:

```bash
source .venv/bin/activate
```

4. **Install dependencies**

```bash
pip install tensorflow keras numpy pillow
```

---

## ▶️ How to Run

Run the Python script:

```bash
python main.py
```

During execution:

* The model trains for 5 epochs
* Validation accuracy is displayed
* Final test accuracy is printed
* A prediction for the first test image is shown

---

## 📊 Sample Output

```text
Epoch 5/5
accuracy: ~0.99
val_accuracy: ~0.98
Test accuracy: 98.xx%
Prediction for first test image: 7
```

---

## 🔍 Key Features

* CNN-based image classification
* Proper image normalization
* One-hot encoded labels
* Clean and beginner-friendly implementation
* Compatible with **Keras 3** imports

---

## 🚀 Future Improvements

* Add model saving & loading
* Visualize predictions with matplotlib
* Implement EarlyStopping callback
* Extend to custom image datasets

---

## 👨‍💻 Author

**Abdullah Ali**
Flutter & Python Developer

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for learning and educational purposes.

---

⭐ If you found this project helpful, consider giving it a star!
