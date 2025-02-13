# ANN-Based Churn Classification

## Overview
This repository contains an Artificial Neural Network (ANN) model designed for customer churn classification. The goal of this project is to predict whether a customer is likely to churn based on various input features. The model is implemented using TensorFlow/Keras and trained on structured customer data.

## Features
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **ANN Architecture**:
  - Input layer with appropriate feature size
  - Multiple hidden layers with activation functions
  - Output layer with a softmax or sigmoid activation function (depending on classification type)
- **Model Training**: Using optimization techniques like Adam and loss functions like binary cross-entropy.
- **Performance Evaluation**: Accuracy, confusion matrix, and classification report.

## Live Demo
Check out the live demo of the project: [ANN Churn Classification](https://ann-churn-classification-ddv23.streamlit.app/)

## Installation
To set up the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/ddv2311/ANN-Churn-Classification.git
cd ANN-Churn-Classification

# Create a virtual environment (optional)
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```
## Usage

```bash

python train.py
python evaluate.py

