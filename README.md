# Telecom Churn Analyzer

This repository contains a Jupyter Notebook for predicting customer churn in a telecom dataset using logistic regression. The model analyzes customer data to identify factors leading to churn and evaluates performance with metrics like accuracy, ROC-AUC, and confusion matrix.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Customer churn prediction is crucial for telecom companies to retain customers. This project uses machine learning to build a binary classification model that predicts whether a customer will churn (leave the service) based on features like account length, international plan, voice mail plan, usage minutes, and customer service calls.

The notebook demonstrates:
- Data loading and exploration
- Preprocessing (handling categorical variables, scaling)
- Model training with Logistic Regression
- Evaluation using accuracy, precision, recall, F1-score, confusion matrix, and ROC curve

## Dataset
The dataset is from [Kaggle's Telecom Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (or similar BigML source). It includes:
- **Training Data**: `churn-bigml-80.csv` (2666 entries)
- **Test Data**: `churn-bigml-20.csv` (667 entries)

Key columns:
- `State`, `Account length`, `Area code`, `International plan`, `Voice mail plan`
- Usage metrics: `Total day minutes`, `Total eve minutes`, etc.
- Target: `Churn` (boolean: True/False)

**Note**: The CSV files are not included in this repo due to size/privacy. Download them from the source and place in the project directory.

## Requirements
- Python 3.10+
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`

## Installation
1. Clone the repository:
git clone https://github.com/your-username/telecom-churn-analyzer.git
cd telecom-churn-analyze
