# Bank Fraud Detection with Machine Learning

An end-to-end machine learning project for detecting fraudulent financial transactions using supervised learning techniques.

---

## Key Points

- End-to-end ML pipeline
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Hyperparameter Optimization
- Imbalanced Classification
- XGBoost, Random Forest & Logistic Regression

---

## Project Overview

Fraud detection is a challenging binary classification problem because fraudulent transactions represent only a very small fraction of all banking operations.

This project builds and compares several machine learning models to accurately identify fraudulent transactions while minimizing false positives.

---

## Dataset

This project uses the **PaySim** synthetic financial transaction dataset.

Due to licensing and repository size limitations, the dataset is **not included** in this repository.

You can download it from Kaggle:

https://www.kaggle.com/datasets/ealaxi/paysim1

After downloading, place the dataset inside:

```
data/
```

---

## Workflow

```
Raw Dataset
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Evaluation
      │
      ▼
Final XGBoost Model
```

---

## Models Evaluated

- Logistic Regression
- Random Forest
- XGBoost

---

## Evaluation Metrics

Since fraud detection is a highly imbalanced classification problem, the project focuses on:

- Precision
- Recall
- F1-score
- ROC-AUC
- Average Precision
- Precision-Recall Curve
- Confusion Matrix

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib

---

## Repository Structure

```
.
├── notebooks/
│   ├── Analysis.ipynb
│   └── Model.ipynb
├── models/
├── data/
│   ├── raw/
│   └── processed/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/<your-username>/bank-fraud-detection.git
```

Create a virtual environment

```bash
python -m venv .venv
```

Activate it

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Cost-sensitive learning
- Probability calibration
- REST API deployment

---
