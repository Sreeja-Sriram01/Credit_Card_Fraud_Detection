# Credit_Card_Fraud_Detection Using SMOTE,XG Boost
__________________________________________________________________________________________________________________________________________________________________________________
![image](https://github.com/user-attachments/assets/a76dcac2-4196-446f-a196-4d4760b211d3)


This project focuses on detecting fraudulent credit card transactions using advanced machine learning techniques. It addresses the highly imbalanced nature of fraud data by applying SMOTE (Synthetic Minority Over-sampling Technique) for balancing and XGBoost for high-performance classification.

_____________________________________________________________________________________________________________________________________________________________________________________________________________

 Technology Used:

 Packages: pandas, matplotlib, seaborn, numpy, sklearn, imblearn

 Handling class imbalance (SMOTE)

 Model: XGBoost Classifier

____________________________________________________________________________________________________________________________________________________________________________________________

Dataset
Source : Kaggle - https://www.kaggle.com/mlg-ulb/creditcardfraud

The datasets contains transactions made by credit cards in September 2013 by european cardholders that occurred in two days.

It contains only numerical input variables which are the result of a PCA transformation. The only features which have not been transformed with PCA are 'Time' and 'Amount'.

___________________________________________________________________________________________________________________________________________________

Folder Structure

 Credit Card Fraud Detection
 
 | credit_card_fraud_detection.ipynb
 
 | README.md
 
 | dataset.csv 
 ___________________________________________________________________________________________________________________________________________________________________________________
 Project Detail
 
Handling Imbalanced Dataset: For this project we use SMOTE (Synthetic Minority Over-sampling Technique) technique to handle imbalanced dataset.

Machine Learning Models: For this project I will implement the data to these models and determine which one fits the best:

Logistic Regression

Decision Tree

Naive Bayes

K-Nearest Neighbor

Support Vector Machine

Random Forest

XGBoost

Model Parameter: To determine which machine learning model fits the dataset the best, I will use this parameter to decide:

Precision-Recall

F1-Score

Accuracy
________________________________________________________________________________________________________________________________________________________
Data Wrangling

Scaling the 'Amount' and 'Time' columns

Use SMOTE to handle imbalanced dataset and see the correlation of each columns

Determine which feature have a negative and positive correlation

Remove extereme outliers from features that have a high correlation with the classes

_____________________________________________________________________________________________________________________________________________________________________________________

Data Analysis

Decide which technique fits the best for the imbalanced dataset. 
![image](https://github.com/user-attachments/assets/3a55bacc-e998-4c43-9625-54442ba27753)
____________________________________________________________________________________________________________________________________________________________
Handling Skewness

The data is heavily skewed therefore we use a power transformer to remove the skewness. Dataset before using power transformer- alt text Dataset after using power transformer- 

![image](https://github.com/user-attachments/assets/6ce0ef25-7eb0-45b1-b72e-fd0d3e2abd12)

![image](https://github.com/user-attachments/assets/1919c16e-f040-451c-ac95-9bdb46ae4dea)


____________________________________________________________________________________________________________________________________________________________
Results

~The XGBoost model achieved 99.93% accuracy, with a precision of 94.06% and recall of 71.15%.

~It correctly detected most fraud cases while keeping false alarms low.
____________________________________________________________________________________________________________________________________________

Conclusion

~Using SMOTE with XGBoost proved effective for handling imbalanced fraud data.

~The model shows strong performance and can be scaled for real-world fraud detection systems.



























