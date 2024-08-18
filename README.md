# Customer Churn Prediction Using ANN

## Overview

This project aims to predict customer churn using an Artificial Neural Network (ANN). The dataset used for this project is the "telephone" dataset from Kaggle, which includes various features related to customer interactions and behavior.

## Dataset

The dataset is available on Kaggle [here](https://www.kaggle.com/datasets). Please download and place the dataset in the `data/` directory of this repository.

## Workflow

1. **Data Collection**: Obtain the "telephone" dataset from Kaggle and place it in the `data/` directory.
2. **Data Preprocessing**: 
   - Load and preprocess the data in `train.py`.
   - Split the data into training and testing sets.
   - Scale features using `StandardScaler`.
3. **Model Training**:
   - Build an ANN model using TensorFlow/Keras in `train.py`.
   - Train the model and save it to the `model/` directory.
4. **Model Evaluation**:
   - The trained model achieves an accuracy of 80% on the test data.
5. **Prediction**:
   - Use `predict.py` to make predictions on new data.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/customer-churn-prediction-ann.git
cd customer-churn-prediction-ann
pip install -r requirements.txt
