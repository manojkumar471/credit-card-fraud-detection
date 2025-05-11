# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent transactions using Machine Learning techniques.

---

## 📁 Dataset
- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Features:** 30+ anonymized features, including `Time`, `Amount`
- **Target Column:** `Class` (0 = normal, 1 = fraud)

---

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## ⚙️ Steps Performed
1. Data cleaning and sampling (10%)
2. Train-test split
3. Model training using **Logistic Regression**
4. Evaluation using confusion matrix and classification report
5. Visualization of fraud vs non-fraud transactions

---

## 📊 Results (Sample)

| Metric     | Value |
|------------|--------|
| Accuracy   | ~99.9% |
| Precision  | 33% (fraud) |
| Recall     | 33% (fraud) |
| F1-Score   | 33% (fraud) |

---

## 📌 How to Run

1. Clone the repository
2. Open `fraud_detection.ipynb` in VS Code or Jupyter
3. Run all cells

```bash
pip install -r requirements.txt
