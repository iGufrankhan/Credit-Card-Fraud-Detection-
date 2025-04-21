# 💳 Credit Card Fraud Detection

This project analyzes and detects fraudulent transactions using machine learning models on the widely-used `creditcard.csv` dataset. The dataset is highly imbalanced, making it a great candidate for unsupervised anomaly detection algorithms such as Isolation Forest and Local Outlier Factor.

---

## 📂 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Transactions: 284,807
- Fraudulent Transactions: 492 (0.17%)
- Features:
  - `Time`, `Amount`
  - `V1` to `V28`: Anonymized PCA-transformed features
  - `Class`: Target variable (`0` = Legitimate, `1` = Fraud)

---

## 🚀 Project Objective

To compare multiple models for fraud detection:
- ✅ Isolation Forest
- ✅ Local Outlier Factor (LOF)
- ✅ Support Vector Machine (SVM)

We evaluate each model based on:
- Accuracy
- Precision & Recall
- Fraud Detection Rate

---

## 📊 Results Summary

| Model              | Errors Detected | Accuracy   | Fraud Detection Rate |
|-------------------|------------------|------------|----------------------|
| Isolation Forest  | 73               | **99.74%** | **27%**              |
| LOF               | 97               | 99.65%     | 2%                   |
| SVM               | 8516             | 70.09%     | 0%                   |

✅ **Isolation Forest** showed the best performance, identifying the most frauds with the highest accuracy.

---

## 🧠 Future Improvements

- Use **larger sample sizes** for training
- Apply **deep learning** techniques (e.g., Autoencoders, LSTM)
- Explore **advanced anomaly detection** frameworks
- Consider **real-time streaming detection** scenarios

---

## 📁 Project Structure

