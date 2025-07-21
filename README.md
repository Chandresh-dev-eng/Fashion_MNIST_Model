# 👕 FashionMNIST Models using PyTorch

This project contains three different deep learning models built and trained on the FashionMNIST dataset using PyTorch. It includes a basic linear model, a two-layer neural network, and a convolutional neural network (CNN) for image classification.

## 📚 Models

1. **FashionMNISTmodel**  
   A simple fully connected network (single hidden layer).

2. **FashionMNISTNon**  
   A two-layer fully connected network with ReLU activations.

3. **FashionMNISTcnn**  
   A convolutional neural network built with multiple convolutional and pooling layers for better feature extraction.

## 🧠 Dataset

The [FashionMNIST dataset](https://github.com/zalandoresearch/fashion-mnist) is a drop-in replacement for the original MNIST dataset, consisting of grayscale 28×28 pixel images of 10 different types of clothing:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## 🛠️ Project Features

- Model training and evaluation with PyTorch
- Random test sample predictions with visualizations
- Accuracy comparison between models
- Custom CNN model with `nn.Conv2d`, `nn.MaxPool2d`, and `nn.Sequential`

## 🖼️ Sample Prediction Plot

Each subplot shows predicted vs true label with color indication:

- ✅ Green → Correct Prediction
- ❌ Red → Wrong Prediction

## 🧪 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fashionmnist-models-pytorch.git
   cd fashionmnist-models-pytorch
