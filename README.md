# 💳 Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using a classification model. The model is trained on real-world anonymized credit card transaction data and aims to distinguish between legitimate and fraudulent transactions with high accuracy.

---

## 📌 Project Objective

The goal is to build a predictive model that can **identify fraudulent credit card transactions** based on transaction details. This helps banks and financial institutions **minimize financial losses** and **improve security**.

---

## 🧠 Algorithms Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- Isolation Forest (for anomaly detection)
- Neural Networks (optional)

---

## 📊 Dataset

- **Dataset Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Details**:
  - 284,807 transactions
  - 492 frauds (highly imbalanced)
  - Features are anonymized (V1, V2, ..., V28)
  - Time and Amount are not anonymized

---

## ⚙️ Technologies Used

| Category      | Tools/Technologies           |
|---------------|------------------------------|
| Language      | Python                       |
| Libraries     | NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn |
| Model Building| Logistic Regression, Tree-based models, XGBoost |
| Visualization | Seaborn, Matplotlib          |
| Evaluation    | Confusion Matrix, ROC-AUC, Precision-Recall Curve |

---

🧪 Model Evaluation Metrics

    Accuracy

    Precision

    Recall

    F1-Score

    ROC-AUC Score

    ⚠️ Note: Because the dataset is highly imbalanced, metrics like precision, recall, and ROC-AUC are more reliable than accuracy.

🔐 Imbalanced Data Handling

    Under-sampling / Over-sampling

    SMOTE (Synthetic Minority Over-sampling Technique)

    Anomaly Detection Techniques (e.g., Isolation Forest, One-Class SVM)

📷 Visualizations

    Distribution of fraud vs. non-fraud

    Correlation matrix

    Precision-recall curve

    Confusion matrix heatmap

    Feature importance (for tree-based models)
