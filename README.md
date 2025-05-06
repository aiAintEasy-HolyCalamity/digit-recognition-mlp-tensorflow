# digit-recognition-mlp-tensorflow
Neural network classifier for handwritten digit recognition using TensorFlow and Keras. Implements ReLU and Softmax functions, trains a 3-layer dense neural network on digit data, and explores basic concepts of multiclass classification.

# Digit Recognition using Neural Networks

This project implements a multi-layer neural network to recognize handwritten digits (0–9) using TensorFlow and Keras. The network is built using `Sequential` API with `Dense` layers and ReLU activation. It outputs class probabilities using the Softmax function. This exercise is part of a foundational deep learning course.

## Features
- ReLU activation function implementation
- Custom Softmax function using NumPy
- 3-layer fully connected neural network (MLP)
- TensorFlow/Keras Sequential model
- Model summary and parameter analysis

## Model Architecture
- Layer 1: Dense(25), ReLU, input shape (400,)
- Layer 2: Dense(15), ReLU
- Layer 3: Dense(10), Output logits

## Skills Learned
- Activation functions (ReLU, Softmax)
- Vectorized operations with NumPy
- TensorFlow model construction
- Understanding multiclass classification

## Getting Started
1. Clone the repo  
2. Open `C2_W2_Assignment.ipynb` in Jupyter or Colab  
3. Run all cells to explore functionality

## Requirements
- Python 3.7+
- TensorFlow
- NumPy
- Matplotlib

## License
MIT License
