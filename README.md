# Flood Probability Prediction Using Machine Learning

This project predicts the probability of flood events using a combination of data processing, visualization, and a neural network classifier built with TensorFlow and scikit-learn.

## Description

The script performs data analysis and outlier removal, visualizes feature relationships, and builds a binary classification model to determine flood probability based on environmental and infrastructural features.

## Installation

1. Clone this repository and navigate to the project folder.
2. Install the required dependencies:
   bash
3. Ensure the dataset file flood.csv is available in the project directory.

## Usage

- Run the script in a Jupyter Notebook or Python environment.
- The script:
  - Loads, summarizes, and cleans the dataset.
  - Performs outlier capping and basic exploratory data analysis (EDA).
  - Builds and evaluates a neural network for flood classification.

## Project Structure

- **untitled0.py**: Main analysis and model training script.
- **flood.csv**: Input dataset file (ensure to provide your own).

## Features

- Data loading and preprocessing
- Outlier capping for numeric features
- Correlation heatmap and boxplot visualization
- Label encoding, feature scaling
- Neural network classifier with early stopping
- Confusion matrix evaluation and results visualization.

## Results

- Binary classifier using XGboost classifier and Keras/TensorFlow with evaluation using a confusion matrix and accuracy metrics.
- The XGBoost classifier achieved an accuracy of 97% on the test set, demonstrating highly effective performance for flood probability prediction.
- Users can compare this accuracy with the neural network classifier’s results for informed model selection.

## Contributing

Pull requests and suggestions are welcome. Please open issues to discuss potential changes.
