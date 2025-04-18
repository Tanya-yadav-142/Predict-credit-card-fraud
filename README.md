<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Credit Card Fraud Detection Project</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 30px;
            line-height: 1.6;
        }
        h1, h2 {
            color: #2c3e50;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: monospace;
        }
        .section {
            margin-bottom: 40px;
        }
        .highlight {
            background-color: #eaf2f8;
            padding: 10px;
            border-left: 5px solid #3498db;
            border-radius: 5px;
        }
        ul {
            list-style: square;
        }
        footer {
            text-align: center;
            font-size: 14px;
            color: #999;
            margin-top: 50px;
        }
    </style>
</head>
<body>

    <h1>🛡️ Credit Card Fraud Detection using Machine Learning</h1>

    <div class="section">
        <h2>📁 Dataset</h2>
        <p><strong>Name:</strong> <code>7. Predict Credit Card Fraud.csv</code><br>
           <strong>Records:</strong> 284,807 transactions<br>
           <strong>Features:</strong> 30 input features + 1 target (<code>Class</code>)</p>
        <p><strong>Target:</strong></p>
        <ul>
            <li><code>Class = 0</code>: Legitimate Transaction</li>
            <li><code>Class = 1</code>: Fraudulent Transaction</li>
        </ul>
    </div>

    <div class="section">
        <h2>📌 Problem Statement</h2>
        <div class="highlight">
            Detect fraudulent credit card transactions using machine learning and address the class imbalance using SMOTE.
        </div>
    </div>

    <div class="section">
        <h2>⚙️ Technologies Used</h2>
        <ul>
            <li>Python</li>
            <li>Scikit-learn</li>
            <li>Pandas</li>
            <li>Matplotlib & Seaborn</li>
            <li>imbalanced-learn (SMOTE)</li>
            <li>Google Colab</li>
        </ul>
    </div>

    <div class="section">
        <h2>🧪 Methodology</h2>
        <ol>
            <li><strong>Data Loading:</strong> Read CSV into pandas DataFrame</li>
            <li><strong>Preprocessing:</strong> Handled missing values, analyzed data</li>
            <li><strong>Balancing:</strong> Used SMOTE to balance fraud/legit classes</li>
            <li><strong>Modeling:</strong> Applied Random Forest Classifier</li>
            <li><strong>Evaluation:</strong> Used accuracy, precision, recall, F1-score</li>
        </ol>
    </div>

    <div class="section">
        <h2>✅ Results</h2>
        <ul>
            <li><strong>Accuracy:</strong> ~99% (with balanced classes)</li>
            <li><strong>Balanced Data:</strong> 284,315 fraud & 284,315 legit after SMOTE</li>
            <li><strong>Model:</strong> Random Forest – effective on rare class detection</li>
        </ul>
    </div>

    <div class="section">
        <h2>📸 Screenshots</h2>
        <p>Included in the notebook:</p>
        <ul>
            <li>Dataset preview</li>
            <li>Before and after class distribution using SMOTE</li>
            <li>Confusion matrix & evaluation metrics</li>
        </ul>
    </div>

    <div class="section">
        <h2>📂 How to Run</h2>
        <ol>
            <li>Upload the dataset in Google Colab</li>
            <li>Paste the provided code in notebook cells</li>
            <li>Run all cells to preprocess, train and evaluate the model</li>
        </ol>
    </div>

    <div class="section">
        <h2>👩‍💻 Author</h2>
        <p><strong>Tanya Yadav</strong><br>
        B.Tech CSE (AI & ML)<br>
        KIET Group of Institutions</p>
    </div>

    <div class="section">
        <h2>🔗 References</h2>
        <ul>
            <li><a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud" target="_blank">Credit Card Fraud Dataset (Kaggle)</a></li>
            <li><a href="https://imbalanced-learn.org/stable/" target="_blank">imbalanced-learn documentation (SMOTE)</a></li>
            <li><a href="https://scikit-learn.org/" target="_blank">scikit-learn</a></li>
        </ul>
    </div>

    <footer>
        &copy; 2025 Tanya Yadav | All Rights Reserved.
    </footer>

</body>
</html>


