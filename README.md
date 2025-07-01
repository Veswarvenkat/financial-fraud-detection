# 🛡️ AI for Fraud Detection in Financial Transactions

This project applies machine learning to detect fraudulent financial transactions, using real-world datasets and techniques. Built as part of a 2-month internship with YBI Foundation.

---

## 📘 Project Summary

- **Goal**: Identify fraudulent transactions using AI/ML
- **Model**: Random Forest Classifier
- **Platform**: Google Colab
- **Tools Used**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 📁 Files Included

- `AI_for_fraud_detection_in_financial_transactions.ipynb` → Complete Jupyter Notebook
- `README.md` → This description file
- *(Optional)* `creditcard.csv` → Dataset file (link below)

---

## 📊 Dataset Info

- **Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records**: 284,807 transactions
- **Label**: `Class` column (0 = Non-Fraud, 1 = Fraud)
- **Highly imbalanced dataset** – handled through sampling

---

## 🔧 Workflow Summary

1. Imported libraries (Pandas, NumPy, Sklearn, etc.)
2. Loaded dataset using Google Colab
3. Performed basic EDA: `df.info()`, `df.isnull().sum()`
4. Split into `X` (features) and `y` (target)
5. Used `train_test_split()` to create training and testing sets
6. Trained a `RandomForestClassifier` on a sample of 10,000 rows (for faster runtime)
7. Evaluated the model with:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

---

## 📈 Results

- **Accuracy**: ~99% on test sample
- Model performed well in identifying fraudulent vs non-fraudulent transactions
- Balanced evaluation even on an imbalanced dataset

---

## 🎓 Internship Credit

- **Organization**: YBI Foundation
- **Type**: 2-Month AI/ML Internship
- **Project**: Real-world AI application in fintech

---

## ✅ Conclusion

This project shows how AI can help secure financial systems by detecting unusual or fraudulent activity. It’s a practical demonstration of using supervised machine learning in the financial domain.

---

## 🌐 Dataset Link

You can find the dataset here:  
🔗 [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
