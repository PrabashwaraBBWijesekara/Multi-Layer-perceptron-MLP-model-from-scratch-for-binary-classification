# Multi-Layer-perceptron-MLP-model-from-scratch-for-binary-classification

## Project Overview
The aim of the project is to build a Multi Layer perceptron (MLP) model from scratch for binary classification. That is given an input x output the associated class label 0 or 1. The MLP is built using **Python** and **NumPy**, with all neural network operations—such as forward propagation, backpropagation, and gradient descent—implemented without the use of deep learning libraries like TensorFlow or PyTorch.

The project provides a hands-on understanding of how neural networks work at a low level, giving users a deeper insight into the mechanics of an MLP.

## Features
- **Custom MLP Implementation**: Built from scratch using Python and NumPy, with no high-level deep learning frameworks.
- **Binary Classification**: Designed to solve binary classification problems (e.g., predicting 0 or 1).
- **Manual Backpropagation**: The model implements forward propagation, backpropagation, and weight updates using gradient descent manually.
- **Activation Functions**: ReLU for hidden layers and Sigmoid for the output layer.
- **Loss Function**: Binary cross-entropy for computing the model’s error.
- **Optimizer**: Gradient descent algorithm implemented from scratch.


## Model Architecture

- **Input Layer**: Neurons equal to the number of input features in the dataset.
- **Hidden Layer**: Fully connected layer using the ReLU activation function.
- **Output Layer**: A single neuron with Sigmoid activation to predict binary outcomes (0 or 1).
- **Loss Function**: Binary cross-entropy for computing the loss between the predicted and actual values.
- **Optimizer**: Gradient descent algorithm implemented from scratch for optimizing the weights.

## Example
Using a synthetic dataset for binary classification, the model achieved over 90% accuracy after training for 500 epochs.

## Results
- **Accuracy**: The MLP model performs well on binary classification tasks, achieving high accuracy for 1 and 5 98.77% and for 7 and 9 94.96%.
- **Loss Plot**: The training loss consistently decreases, indicating successful learning.
