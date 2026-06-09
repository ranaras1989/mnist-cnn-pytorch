# MNIST Handwritten Digit Recognition using CNN and PyTorch

## Project Overview

This project implements a Convolutional Neural Network (CNN) in PyTorch to recognize handwritten digits from the MNIST dataset.

The model learns image features such as edges, curves, and shapes using convolutional layers and achieves high classification accuracy on unseen test images.

## Dataset

MNIST Dataset

* 60,000 training images
* 10,000 test images
* 10 digit classes (0–9)
* Image size: 28 × 28 grayscale

## Technologies Used

* Python
* PyTorch
* TorchVision
* Jupyter Notebook

## CNN Architecture

Input Image (1×28×28)

→ Conv2D (1 → 16)

→ ReLU

→ MaxPool

→ Conv2D (16 → 32)

→ ReLU

→ MaxPool

→ Flatten

→ Fully Connected Layer

→ Output (10 Classes)

## Results

Test Accuracy: 98.92%

## Files

* mnist_cnn_pytorch.ipynb
* mnist_cnn.pth

## Author

Rana Bihari
