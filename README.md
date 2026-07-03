# 🧠 Handwritten Digit Classification using Perceptron, ANN & CNN

A Deep Learning project that implements and compares three neural network architectures—**Perceptron**, **Artificial Neural Network (ANN)**, and **Convolutional Neural Network (CNN)**—for handwritten digit recognition using the **MNIST** dataset.

The objective of this project is to understand how model complexity influences performance and why CNNs outperform traditional neural networks on image classification tasks.

---

## 📖 Project Overview

Image classification is one of the most fundamental applications of Deep Learning. In this project, three different neural network architectures are trained and evaluated on the MNIST handwritten digit dataset.

The models are compared using performance metrics such as:

- Training Accuracy
- Validation Accuracy
- Training Loss
- Validation Loss

This comparison provides a clear understanding of how neural network architectures evolve from simple linear models to powerful convolutional networks.

---

## 📂 Dataset

**Dataset:** MNIST Handwritten Digits

- 70,000 grayscale images
- Image Size: **28 × 28 pixels**
- 10 Classes (Digits 0–9)

Dataset is loaded directly using TensorFlow/Keras.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow
- Keras
- Scikit-learn

---

## 🚀 Models Implemented

### 1️⃣ Perceptron

A single-layer neural network that serves as the baseline model.

**Architecture**

- Flatten Layer
- Dense Layer (Softmax)

---

### 2️⃣ Artificial Neural Network (ANN)

A fully connected feedforward neural network capable of learning non-linear relationships.

**Architecture**

- Flatten Layer
- Dense (128, ReLU)
- Dense (64, ReLU)
- Output Layer (Softmax)

---

### 3️⃣ Convolutional Neural Network (CNN)

A deep learning architecture specifically designed for image recognition.

**Architecture**

- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten
- Dense (128, ReLU)
- Dropout
- Output Layer (Softmax)

---

## 📊 Workflow

- Load MNIST Dataset
- Data Preprocessing
- Normalize Pixel Values
- Build Neural Network Models
- Train Models
- Evaluate Performance
- Compare Accuracy & Loss Curves

---

## 📈 Results

The project compares the performance of:

- Perceptron
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

using:

- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

CNN achieves the highest performance due to its ability to learn spatial features directly from image data.

---

## 📷 Sample Outputs

- Training Accuracy
- Validation Accuracy
- Loss Curves
- Model Evaluation Metrics

(Add screenshots here)

---

## 📁 Project Structure

```
├── CNN.ipynb
├── README.md
└── images/
    ├── accuracy.png
    ├── loss.png
    └── prediction.png
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/puneetraghav-dev/Handwritten-Digit-Classification.git
```

Install dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

Run the notebook

```bash
jupyter notebook CNN.ipynb
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Deep Learning Fundamentals
- Neural Networks
- Perceptron
- Artificial Neural Networks
- Convolutional Neural Networks
- Image Classification
- TensorFlow/Keras
- Model Evaluation
- Data Preprocessing

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Batch Normalization
- Data Augmentation
- Transfer Learning
- Model Deployment with Streamlit/Flask
- Real-time handwritten digit prediction

---

## 👨‍💻 Author

**Puneet Raghav**

Aspiring AI Engineer passionate about Machine Learning, Deep Learning, NLP, and building real-world AI applications.

📧 Connect with me on LinkedIn and GitHub!

If you found this project helpful, don't forget to ⭐ star the repository!
