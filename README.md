# Robust-Anomaly-Detection-For-High-Dimensional-Time-Series
Robust anomaly detection system for high-dimensional industrial sensor time-series data using Isolation Forest and Autoencoder models. Includes synthetic data generation, preprocessing, anomaly scoring, visualization, and performance evaluation with Accuracy, Precision, Recall, and F1 Score using Python and Scikit-learn.

## Overview

This project focuses on detecting anomalies in high-dimensional industrial sensor time-series data using Machine Learning and Deep Learning techniques. It uses Isolation Forest and Autoencoder-based models to identify unusual patterns in multivariate data.

## Features

* Synthetic multivariate time-series dataset generation
* Data preprocessing and feature scaling
* Isolation Forest anomaly detection
* Autoencoder anomaly detection
* Performance evaluation using Accuracy, Precision, Recall, and F1 Score
* Visualization of anomaly scores and results

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Project Structure

```text
robust-anomaly-detection/
│── main.py
│── notebook.ipynb
│── requirements.txt
│── README.md
│── project_report.docx
```

## Installation

```bash
pip install -r requirements.txt
```

## Run Project

```bash
python main.py
```

## Models Used

### 1. Isolation Forest

Tree-based anomaly detection model for identifying outliers.

### 2. Autoencoder

Neural network model that detects anomalies using reconstruction error.

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

## Future Improvements

* Real-time anomaly detection
* IoT sensor deployment
* SHAP explainability
* LSTM Autoencoders
