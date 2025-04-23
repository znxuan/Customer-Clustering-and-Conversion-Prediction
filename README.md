# Customer-Clustering-and-Conversion-Prediction

>  Submission for: **Data Titans Hackathon – Solving Business & Economic Challenges with Analytics**

## Theme
Consumer Behavior & Business Strategy

*What drives customer spending habits, and how can businesses optimize pricing strategies?*

## Overview

In this project, we analyze customer behavioral patterns to:

- Identify customer segments through **clustering**
- Predict customer **conversion probability**
- Provide strategic insights to optimize **marketing**, **pricing**, and **personalization** tactics

Our solution was built and submitted for the **Data Titans Hackathon**, leveraging data science to tackle real-world economic and business strategy challenges.Businesses are increasingly facing challenges in understanding the **diversity of their customer base**. Without personalized strategies, they often overspend on ineffective marketing campaigns. This project addresses two core questions:

1. How can we segment customers based on spending habits and behaviors?
2. Can we predict customer conversion using historical data?

## Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-yellow?style=for-the-badge&logo=python&logoColor=white)
![numpy](https://img.shields.io/badge/numpy-green?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-red?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-00A3A7?style=for-the-badge&logo=seaborn&logoColor=white)
![xgboost](https://img.shields.io/badge/xgboost-3D8DCA?style=for-the-badge&logo=xgboost&logoColor=white)

## Data & Features

The dataset includes:

- Demographic details (e.g., Age, Income, Location)
- Transactional behavior (e.g., Frequency, Amount Spent)
- Channel interaction metrics (e.g., Email Clicks, Online Visits)
- Labels indicating **conversion status**

## Model Training & Evaluation

#### Clustering

- KMeans Clustering: Unsupervised segmentation
- Elbow Method & Silhouette Score: Optimal cluster number

#### Classification

- Logistic Regression
- Random Forest
- XGBoost
- Grid Search CV: Hyperparameter tuning
- ROC-AUC, Precision, Recall, F1: Model evaluation

## Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/Customer-Clustering-and-Conversion-Prediction.git
cd Customer-Clustering-and-Conversion-Prediction
```

Install the dependencies:
```bash
pip install -r requirements.txt
```
