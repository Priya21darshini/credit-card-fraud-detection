# Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent transactions in credit card data using various supervised machine learning algorithms. Due to the highly imbalanced nature of the dataset, special attention is given to precision, recall, and other evaluation metrics beyond simple accuracy.

---

## 📌 Problem Statement

Credit card fraud is a serious concern in the financial sector. The aim of this project is to build predictive models that can accurately identify fraudulent transactions while minimizing false positives.

---

## 📁 Dataset

- **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Records:** 284,807 transactions
- **Features:** 30 numerical features (V1–V28 are PCA-transformed), Time, Amount
- **Target:** `Class` (0 = Legitimate, 1 = Fraudulent)
- **Imbalance:** ~0.17% of the transactions are frauds

---

## 🧹 Data Preprocessing

- Checked for missing values and duplicates
- Performed basic EDA (class distribution, amount distributions, etc.)
- Handled class imbalance by analyzing precision, recall, and using appropriate metrics
- Features were already PCA-transformed, so minimal feature engineering was required

---

## 🧠 Models Used

The following classification algorithms were applied and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📊 Evaluation Metrics

Since this is an **imbalanced classification problem**, the following metrics were prioritized:

- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-Score**
- **Accuracy** (used but not the main metric)

---

## ✅ Results Summary

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Logistic Regression| ~        | ~         | ~      | ~        |
| Decision Tree      | ~        | ~         | ~      | ~        |
| Random Forest      | ~        | ~         | ~      | ~        |

*Note: Fill in the actual values from your notebook if desired.*

---

## 📦 Technologies Used

- Python
- Jupyter Notebook
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn

---

## 💡 Key Learnings

- Handling highly imbalanced datasets
- Importance of precision and recall in fraud detection
- Trade-offs between model complexity and interpretability
- Evaluating model performance beyond accuracy

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
