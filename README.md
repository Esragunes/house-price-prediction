# House Price Prediction

This project aims to predict house prices based on various features using machine learning techniques, primarily Linear Regression. The dataset is from Kaggle's House Prices competition.

---

## Overview

The dataset contains various features describing the houses and their sale prices. The goal is to build a model that can accurately predict house prices based on these features.

---

## Steps Covered

### Data Cleaning

- Handling missing values by imputing medians for numerical columns and "None" for categorical columns.  
- Dropping columns with more than 80% missing data.  

### Feature Engineering

- Encoding categorical variables using One-Hot Encoding.  
- Aligning training and test datasets to have the same features.  

### Modeling

- Training a Linear Regression model on the training data.  
- Evaluating model performance using RMSE and R2 score on a validation set.  
- Predicting house prices on the test set.  

---

## Key Observations

- Some features had high missing values and were dropped to improve model quality.  
- Log transformation helped normalize the target variable `SalePrice`.  
- Linear Regression provided a baseline model with reasonable accuracy.  

---

## How to Use

Download or clone this repository. You can open the notebook in Google Colab or Jupyter Notebook to run the analysis step by step.

---

## Files

- `train.csv`: Training data with house features and sale prices.  
- `test.csv`: Test data with house features for prediction.  
- `submission.csv`: Final prediction file for submission.  
- `house_price_prediction.ipynb`: Jupyter Notebook with full code and explanations.  

---

## Author

Created by EsraGunes. Feel free to reuse or adapt this work.
