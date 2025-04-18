# Predict-credit-card-fraud
🛡️ Credit Card Fraud Detection using Machine Learning
📁 Dataset
Name: 7. Predict Credit Card Fraud.csv

Records: 284,807 transactions

Features: 30 input features (V1–V28, Time, Amount) and 1 target feature (Class)

Target:

Class = 0: Legitimate Transaction

Class = 1: Fraudulent Transaction

📌 Problem Statement
Detect fraudulent credit card transactions using machine learning and handle the class imbalance problem using SMOTE (Synthetic Minority Oversampling Technique).

⚙️ Technologies Used
Python

Scikit-learn

Pandas

Matplotlib & Seaborn

imbalanced-learn (SMOTE)

Google Colab

🧪 Methodology
Data Loading: Loaded CSV dataset into pandas dataframe.

Preprocessing:

Checked for missing values.

Visualized and analyzed the distribution of the Class feature.

Balancing Dataset:

Applied SMOTE to address heavy class imbalance (legit vs fraud).

Model Training:

Used Random Forest Classifier (optimized with fewer estimators and limited depth for speed).

Evaluation:

Calculated accuracy, precision, recall, F1-score.

Plotted a confusion matrix.

✅ Results
Accuracy: ~99% (varies slightly with random state)

Balanced Dataset: Achieved equal class distribution using SMOTE.

Model: Performs well on detecting rare fraud cases.

📸 Screenshots (in notebook)
Dataset preview

Class distribution before and after SMOTE

Confusion matrix

Model accuracy & classification report

📂 How to Run
Upload the dataset to Google Colab (7. Predict Credit Card Fraud.csv)

Copy and paste the complete code into a Colab notebook.

Run all cells to preprocess, train, and evaluate the model.

👩‍💻 Author
Tanya Yadav
B.Tech CSE (AI & ML)
KIET Group of Institutions

🔗 References
Dataset Source: Kaggle – Credit Card Fraud Detection

SMOTE: imbalanced-learn documentation

Scikit-learn: https://scikit-learn.org/

