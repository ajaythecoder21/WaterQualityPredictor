# WaterQualityPredictor

## Overview
The Water Quality Predictor will be able to predict if the water is safe or not based on a variety of features, such as pH, Sulfates, Conductivity, Organic Carbon, and many other features.  This could be used to help prevent contamination and to support the use of safe water.
## Dataset
- Used Kaggle Water Quality Dataset
- Features
  - pH
  - Hardness
  - Solids
  - Chloramines
  - Sulfate
  - Conductivity
  - Organic_carbon
  - Trihalomethanes
  - Turbidity
  - Potability

## Feature Engineering
- Handled Missing Values by performing Median Imputation based an Another Feature

## Hyperparameter Tuning
- Used Keras Tuner and Perform Random Search to find optimal number of neurons, layers, learning rate

## Model Building
- Built Artificial Neural Network for Binary Classification
- Optimized model using Adam Optimizer and Binary Crossentropy Loss

## Model Evaluation
- Achieved 95% Accuracy 

## Tools Used
Python (Libraries)
- Tensorflow => Keras
- Scikit-Learn
- Pandas
- NumPy

## Installation
- Install Anaconda Distribution
- Install Python
- Install Libraries
  - pip install numpy
  - pip install sklearn
  - pip install keras-tuner
  - pip install tensorflow
  - pip install pandas
## Resources
https://www.youtube.com/watch?v=RZRoFU_abqU&list=PLZoTAELRMXVPwYGE2PXD3x0bfKnR0cJjN&index=8
https://www.youtube.com/watch?v=Lx16T9cl5ng
