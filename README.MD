# Fraud Detection with Machine Learning

## Overview
This project is a machine learning-based fraud detection system designed to identify fraudulent transactions in financial data. It combines multiple models using an ensemble approach, allowing for more accurate fraud detection by leveraging the strengths of each model.

The project uses:
- **Autoencoder** for anomaly detection
- **Isolation Forest** for outlier detection
- 
- **Random Forest** with SMOTE for class imbalance handling and supervised learning

These models are combined into an ensemble with a weighted voting system, resulting in a robust approach to detecting fraud.

## Project Structure
- `fraud_detection_notebook.ipynb`: Main Jupyter Notebook containing all code for data preprocessing, model training, evaluation, and ensemble setup.
- `README.md`: Project documentation and setup instructions.
- `.gitignore`: Specifies files to be ignored in the repository.

## Features
- **Data Imbalance Handling**: Uses SMOTE (Synthetic Minority Over-sampling Technique) to balance the training dataset, improving model sensitivity to rare fraud cases.
- **Ensemble Model**: Combines three models (Autoencoder, Isolation Forest, Random Forest) for improved precision and recall.
- **Real-Time Simulation**: Tests the model in a simulated real-time environment, providing insights for deployment in real-world applications.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/tushar-1803/fraud_detection_project.git
   cd fraud_detection_project
