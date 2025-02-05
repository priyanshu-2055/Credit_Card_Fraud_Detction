# Credit_Card_Fraud_Detction

Credit Card Fraud Detection
# Overview
This project focuses on detecting fraudulent credit card transactions using a Logistic Regression model. The dataset contains transaction details, customer information, merchant details, and fraud indicators.

# Dataset Description
The dataset consists of multiple features, including:

~Transaction details: trans_date_trans_time, cc_num, merchant, category, amt
~Customer details: first, last, gender, street, city, state, zip, lat, long, city_pop, job, dob
~Transaction identifiers: trans_num, unix_time, merch_lat, merch_long
~Fraud label: is_fraud (0: Not Fraud, 1: Fraud)

# Model Used
~Algorithm: Logistic Regression
~Accuracy Achieved: 0.96

# Steps Performed
~Data Preprocessing

~Handled missing values and duplicates.
~Encoded categorical features.
~Normalized numerical features.
~Exploratory Data Analysis (EDA)

~Visualized transaction amounts and fraud distribution.
~Identified trends in fraudulent transactions.
~Feature Engineering

~Selected relevant features for fraud detection.
~Model Training

~Split data into training and testing sets.
~Trained a Logistic Regression model.

# Evaluation
~Achieved 96% accuracy.
~Evaluated using metrics like Precision, Recall, F1-score, and Confusion Matrix.

# Results
~The model successfully detects fraudulent transactions with high accuracy.
~Logistic Regression provides interpretability, making it a preferred choice for fraud detection.

# Installation & Usage
Clone the repository:
git clone https://github.com/priyanshu-2055/Credit_Card_Fraud_Detction.git

# Install dependencies:
~pip install pandas numpy scikit-learn matplotlib seaborn
~Run the model:
python fraud_detection.py

# Future Improvements
Implement Deep Learning models (LSTMs, Autoencoders) for better accuracy.
Integrate real-time fraud detection for practical applications.

# Author
Priyanshu Kumar
