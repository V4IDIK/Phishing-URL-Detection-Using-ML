# Phishing URL Detection Using Machine Learning

A machine learning project that detects phishing URLs using various classification algorithms. This project analyzes website features to classify URLs as legitimate or phishing.

## Overview

This project implements a machine learning solution to detect phishing URLs by analyzing various website characteristics. The model can help identify malicious websites that attempt to steal user credentials or sensitive information.

## Dataset

The project uses a dataset containing 11,056 URLs with 30 features each. The dataset includes:

- **Size**: 11,056 samples
- **Features**: 30 website characteristics
- **Target**: Binary classification (-1 for phishing, 1 for legitimate)

### Dataset Files
- `phishing.csv` - Main dataset with 11,056 entries
- `dataset.csv` - Alternative dataset version
- `Dataset Website Parameters.txt` - Description of all features

## Features

The model analyzes 30 different website features to detect phishing URLs. These features are categorized into:

### Feature Categories
- **URL-based Features** - URL structure, length, special characters, and domain analysis
- **Security Features** - SSL certificates, domain registration, and HTTPS usage  
- **HTML/JavaScript Features** - External requests, forms, redirects, and interactive elements
- **Domain Features** - Domain age, traffic, PageRank, and reputation metrics

*For a complete list of all 30 features and their descriptions, see `Dataset Website Parameters.txt`*

## Models

The project implements and compares multiple machine learning algorithms:

### 1. Random Forest Classifier
- **Accuracy**: ~93-94%
- Robust ensemble method with good performance

### 2. Logistic Regression
- **Accuracy**: ~92-93%
- Fast and interpretable linear model

### 3. K-Nearest Neighbors (KNN)
- **Accuracy**: ~93-94%
- Instance-based learning algorithm

### Model Evaluation
- Classification reports with precision, recall, and F1-score
- Confusion matrices for detailed performance analysis
- Cross-validation for robust evaluation

## Installation

### Requirements
```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

### Jupyter Notebook Setup
```bash
pip install jupyter
jupyter notebook
```


