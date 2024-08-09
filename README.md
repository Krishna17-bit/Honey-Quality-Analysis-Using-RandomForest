# Honey-Quality-Analysis-Using-RandomForest
## Project Overview
This project utilizes a RandomForest Classifier to analyze the quality of honey based on various spectral data from hyperspectral imaging. It aims to classify honey samples based on their adulteration level.

## Data
The data used in this project includes spectral measurements ranging from `399.40nm` to `1063.79nm` wavelengths, acquired from samples labeled with different adulteration levels.

## Setup and Installation
Ensure you have Python installed on your machine. Clone this repository and install the required packages:

## Usage
To run the model training and evaluation, execute the script:
Honey_analysis_rf_model.py

## Model Details
The RandomForest model is trained with the following configuration:
- Estimators: 100
- Random State: 42
- Class Weight: Balanced

Accuracy achieved on test data is approximately 99.54%.

## Feature Importance
Feature importance analysis is provided to identify which wavelengths are most influential in determining the quality of honey.

