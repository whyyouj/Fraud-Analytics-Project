# BT4012 Group 16 Project - Fraudulent Credit Card Transaction Prediction

## Overview
In this project, our team tackled the challenge of predicting fraudulent credit card transactions. Utilizing a synthetic dataset from Kaggle, we explored various machine learning models to identify key indicators of fraud and enhance predictive accuracy.

## Dataset
The dataset comprises 1,296,675 entries, with 0.579% of the data being fraudulent. Features include transaction details, merchant category, amount, and cardholder information. We conducted thorough data processing, including feature engineering and balancing the class distribution using SMOTE-Tomek Sampling.

## Key Features
Our analysis identified crucial features for fraud detection:
- `Scale_log_amt`: Log transformation of transaction amount.
- `Category_fe`: Frequency encoding of merchant categories.
- `Trans_hour_cos`: Cosine transformation of transaction hour to capture cyclical patterns.

## Models Explored
- Logistic Regression
- Neural Network
- RandomForest
- XGBoost
- Light Gradient Boosting Model

Each model was meticulously tuned and evaluated based on performance metrics such as Accuracy, Precision, Recall, F1 Score, and AUC.

## Results
Our findings highlighted the effectiveness of ensemble models, particularly XGBoost, in handling the complexity and nuances of fraudulent transaction prediction. The project demonstrated the value of combining advanced analytical techniques with machine learning to enhance fraud detection capabilities.

## Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/whyyouj/BT4012-Group-16.git

## Data
Our data can be found here: 
https://drive.google.com/drive/folders/1eI4JKj99mqs5oY5LFCxxJMJHGV_NPNzA?usp=sharing
The dataset is too large to be uploaded to Github
