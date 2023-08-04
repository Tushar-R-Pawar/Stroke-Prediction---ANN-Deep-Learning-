# Stroke-Prediction using ANN (Deep Learning)

This repository contains code for an Artificial Neural Network (ANN) model that predicts the likelihood of a person having a stroke based on various health attributes. The dataset used for training and testing the model is provided in the healthcare-dataset-stroke-data.csv file.

### Model
The ANN model architecture consists of two hidden layers, each with 20 neurons and the ReLU activation function. The output layer has one neuron with the sigmoid activation function, as it is a binary classification problem. The model is trained using the Adam optimizer and binary cross-entropy loss.

### Training and Evaluation
The dataset is split into training and testing sets, and the model is trained on the training data. The training process uses early stopping to prevent overfitting. The model's performance is evaluated on the test data using accuracy and loss metrics.
