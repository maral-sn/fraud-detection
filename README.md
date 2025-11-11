# fraud-detection
Fraud detection project using machine learning algorithms (Logistic Regression, Random Forest)
Added README file with project details
# Fraud Detection Project  

This project focuses on detecting fraudulent credit card transactions using **machine learning algorithms**.  
The dataset used is from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).  

## 🔹 Project Overview  
- Applied **Logistic Regression** and **Random Forest** to classify transactions as fraudulent or legitimate.  
- Preprocessed data (scaling, handling class imbalance, splitting into train/test).  
- Evaluated models using **accuracy, precision, recall, and F1-score**.  

## 🔹 Tools & Technologies  
- **Python**  
- **Pandas, NumPy, Scikit-learn**  
- **Matplotlib, Seaborn**  
- **Jupyter Notebook / Google Colab**  

## 🔹 Challenges & Solutions

- **Challenge:** Extreme class imbalance (0.17% fraud cases)
- **Solution:** Implemented Random Forest with class weighting and SMOTE oversampling
- **Challenge:** Low recall rate for fraud cases in initial models
- **Solution:** Optimized hyperparameters for recall to minimize false negatives

## 🔹 Business Impact

- Reduces financial losses by automatically detecting fraudulent transactions
- Prioritizes high recall (85%) to ensure minimal missed fraud cases
- Enhances customer trust and security in financial systems

## 🔹 Results  
- Logistic Regression: Balanced performance, interpretable model.  
- Random Forest: Higher accuracy, robust against imbalance.  
- Achieved **X% accuracy** and strong recall on fraud cases.  

## 🔹 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/maral_sn/fraud-detection.git 
