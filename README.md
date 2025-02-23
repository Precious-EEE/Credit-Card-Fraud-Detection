

# 💳 Credit Card Fraud Prediction Using ML & DL  

## Overview  
This project focuses on detecting fraudulent credit card transactions using **machine learning (ML) and deep learning (DL) models**. It involves **data preprocessing, exploratory data analysis (EDA), feature engineering, and model training** to distinguish between fraudulent and non-fraudulent transactions.  

## Features  
✅ **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.  
✅ **Exploratory Data Analysis (EDA)**: Visualizing transaction patterns, fraud distributions, and correlations.  
✅ **Feature Engineering**: Selecting relevant features and handling imbalances in fraud cases.  
✅ **Machine Learning Models**:  
   - Logistic Regression  
   - Random Forest  
   - Support Vector Machine (SVM)  
   - XGBoost  
   - CatBoost  
✅ **Deep Learning (DL) Implementation**: Neural Networks for enhanced fraud detection.  
✅ **Model Evaluation**: Using **Accuracy Score, Confusion Matrix, Precision, Recall, and F1-score**.  

## Installation  
Clone the repository and install dependencies:  
```sh
git clone https://github.com/your-repo/credit-card-fraud-prediction.git
cd credit-card-fraud-prediction
pip install -r requirements.txt
```

## Dataset  
The dataset contains transaction records with features such as:  
- **Transaction Type**  
- **Amount**  
- **Old & New Account Balances**  
- **Fraud Flag (0 = Non-Fraud, 1 = Fraudulent Transaction)**  

## Running the Model  
To train and test the fraud prediction model:  
```sh
python creditcard_prediction.py
```

## Model Performance  
The models are evaluated based on accuracy and classification reports:  
📌 **Logistic Regression**: Accuracy ≈ 82%  
📌 **Random Forest**: Accuracy ≈ 99%  
📌 **XGBoost**: Accuracy ≈ 99%  
📌 **CatBoost**: Accuracy ≈ 99%  
📌 **Support Vector Machine (SVM)**: Accuracy ≈ 85%  

## Future Improvements  
🔹 Hyperparameter tuning for improved model performance.   
🔹 Integration with **streaming data pipelines** for live fraud monitoring.  
