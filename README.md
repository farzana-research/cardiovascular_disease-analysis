# Cardiovascular Disease Prediction Project

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-green.svg)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📋 Project Overview

This project aims to predict cardiovascular disease using machine learning models. It analyzes patient health data to identify key risk factors and predict whether a patient has cardiovascular disease. The project implements and compares two classification algorithms: **Logistic Regression** and **Decision Tree Classifier**.

### 🎯 Key Objectives

- Load and explore cardiovascular disease dataset
- Preprocess data (handle missing values, encode categorical variables, scale features)
- Train and evaluate Machine Learning models
- Compare model performance using multiple metrics
- Visualize results with confusion matrices, ROC curves, and feature importance

## 📊 Dataset

**Source**: [Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/colewelkins/cardiovascular-disease) from Kaggle

**Features include**:
- **Demographic**: age, gender
- **Physical**: height, weight
- **Medical**: blood pressure (ap_hi, ap_lo), cholesterol, glucose
- **Lifestyle**: smoking, alcohol intake, physical activity
- **Target**: cardio (0 = No Disease, 1 = Disease)

## 🏗️ Project Structure
cardiovascular-disease-prediction/
│
├── Cardiovascular_Disease_Prediction.ipynb # Main Jupyter Notebook
├── README.md # Project documentation
├── requirements.txt # Required packages
├── data/
│ └── cardiovascular_disease.csv # Dataset (not included in repo)
└── images/
├── confusion_matrix_lr.png # Logistic Regression CM
├── confusion_matrix_dt.png # Decision Tree CM
├── roc_curves.png # ROC curves comparison
└── feature_importance.png # Decision Tree features


## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.7+ installed on your system.

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/cardiovascular-disease-prediction.git
cd cardiovascular-disease-prediction

2. **Install required packages**

```pip install -r requirements.txt