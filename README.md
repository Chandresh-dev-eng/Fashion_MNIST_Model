# FashionMNIST Models

This project explores and compares three deep learning models built using PyTorch to classify clothing images from the FashionMNIST dataset:

- 🔹 **Linear Model** — A simple logistic regression approach using fully connected layers.
- 🔹 **MLP (Multilayer Perceptron)** — A deeper feedforward network with one or more hidden layers.
- 🔹 **CNN (Convolutional Neural Network)** — A convolution-based architecture suitable for image data.

## 🧪 Dataset
FashionMNIST consists of 28×28 grayscale images of 10 fashion categories such as shirts, shoes, trousers, etc.

## 📊 Goal
The goal is to evaluate and compare model performances in terms of accuracy, loss, and prediction quality on a held-out test set.

## 📦 Tools & Libraries
- PyTorch
- Matplotlib
- NumPy

## 🚀 How to Run
```bash
# clone the repository
git clone https://github.com/yourusername/fashion-mnist-models.git
cd fashion-mnist-models

# install dependencies
pip install -r requirements.txt

# run the training script
python train.py
