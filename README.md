# Credit Card Fraud Detection

## Introduction
Credit card fraud is a growing concern in today’s digital economy, leading to substantial financial losses and eroding customer trust. This project implements a machine learning pipeline to identify fraudulent transactions within an anonymized credit card dataset. By leveraging oversampling techniques and ensemble models, it aims to achieve high detection rates while minimizing false alarms.

## Dataset
- **File:** `7. Predict Credit Card Fraud.csv`  
- **Records:** 284,807 transactions  
- **Features:** 30 anonymized features (V1–V28, Time, Amount) + target (`Class`)  
- **Target:** 0 = legitimate, 1 = fraud

## Requirements
- Python 3.x  
- pandas, scikit-learn, imbalanced-learn, seaborn, matplotlib  

## Setup & Usage
1. Upload the CSV to Google Colab  
2. Install dependencies:  
   ```bash
   !pip install pandas scikit-learn imbalanced-learn seaborn matplotlib
