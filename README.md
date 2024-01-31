# Optical Character Recognition (OCR) with MNIST Dataset
# Overview

This repository contains a Jupyter notebook that outlines the process of building and training a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset.

# Prerequisites

To run the notebook, you need the following installed:
Python 3.x
Keras
NumPy
Matplotlib
scikit-learn

# Dataset
The MNIST dataset is automatically downloaded when you run the notebook. It contains 60,000 training images and 10,000 test images of handwritten digits.

# Usage
Open the OCR_MNIST_Data.ipynb notebook in Jupyter Lab or Jupyter Notebook and run the cells sequentially to build and evaluate the model.

# Model Architecture
The model consists of a sequential layer, followed by a convolutional layer, max pooling, flattening, dense layers, and an output layer. It uses categorical crossentropy loss and RMSprop optimizer.

# Training
The model is trained for 2 epochs. You can adjust the number of epochs as needed.

# Evaluation
Evaluate the model's performance using the provided classification report, which includes precision, recall, f1-score, and accuracy metrics.

# Results
The model achieves high accuracy and excellent classification metrics across all digit classes.

# Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.

# License
This project is open-source and available under the MIT License.

This README provides a concise guide on how to set up, run, and understand the project. You can add it to the root of your Git repository to help users navigate and utilize the OCR MNIST notebook. Adjust the content as necessary to match the specific aspects of your project and repository structure.
