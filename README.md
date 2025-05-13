💳 Credit Card Fraud Detection – Project Summary

🔍 Goal:
Detect fraudulent credit card transactions using machine learning on an imbalanced dataset.

📁 Dataset:

Source: Kaggle

284,807 transactions

Only 492 are fraudulent (highly imbalanced)

🔧 Tools Used:

Python, Jupyter Notebook

Pandas, NumPy (data handling)

Matplotlib, Seaborn (visualization)

Scikit-learn, XGBoost (modeling)

📈 Process:

Data cleaning and exploration

Handled imbalance using SMOTE

Trained models: Logistic Regression, Random Forest, XGBoost

Evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC

📊 Results:

Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	98%	94%	88%	91%	0.96
Random Forest	99.8%	99.5%	98.7%	99.1%	0.999
XGBoost	99.9%	99.8%	99.3%	99.5%	0.9995

✅ XGBoost performed the best in detecting fraud with near-perfect metrics.
