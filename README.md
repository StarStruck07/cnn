#CNN on CIFER-10:

This repository contains a Convolutional Neural Network (CNN) model implemented in PyTorch to classify images from the CIFAR-10 dataset. The model is trained and evaluated on the dataset using basic computer vision and deep learning techniques.
The architecture includes:

- 4 convolutional layers with ReLU activation

- 2 max-pooling layers

- Dropout regularization

- Fully connected layers with ReLU and Dropout

- Final classification layer for 10 output classes



Training is conducted using:

- Cross Entropy Loss

- SGD optimizer with momentum and weight decay

- Learning rate scheduler (StepLR)

Dataset: CIFAR-10
Loaded via Hugging Face Datasets: uoft-cs/cifar10

The dataset is normalized and resized to (32x32) with three color channels.

