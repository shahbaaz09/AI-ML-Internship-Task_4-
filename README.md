# AI-ML-Internship-Task_4-
# Logistic Regression - Breast Cancer Classification

This project is part of my AI & ML internship by Elevate Labs, where I built a binary classification model using **Logistic Regression** to predict whether a tumor is malignant or benign using the **Breast Cancer Wisconsin (Diagnostic)** dataset.

---

## 🔍 Problem Statement

To classify tumors into **malignant** or **benign** categories using logistic regression, and evaluate the model using common classification metrics like precision, recall, and ROC-AUC score.

---

## 🧠 Dataset

- **Source**: [Kaggle - Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **File used**: `data.csv`
- **Target Column**: `diagnosis`
  - `M` = Malignant (1)
  - `B` = Benign (0)
- Dataset contains 30 numerical features extracted from medical images.

---

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 🚀 Steps Performed

1. **Loaded** the dataset and removed unnecessary columns.
2. **Encoded** the target variable (`M` → 1, `B` → 0).
3. **Split** the data into training and testing sets.
4. **Standardized** the feature values.
5. **Trained** a logistic regression model.
6. **Evaluated** using:
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve
   - ROC AUC Score

---

## 📊 Evaluation Metrics

Example outputs (will vary slightly each run):

- **Accuracy**: ~95%
- **Precision**: 0.96
- **Recall**: 0.95
- **ROC AUC Score**: 0.99

---

## 📈 ROC Curve

The ROC Curve helps visualize model performance across different classification thresholds.

---

## 📂 Project Structure
.
├── data.csv
├── breast_cancer_logistic_regression.ipynb
└── README.md

---

## ✅ Conclusion

The logistic regression model performed very well on the breast cancer dataset, with high accuracy and ROC-AUC score. This task helped me understand:
- Binary classification fundamentals
- How the sigmoid function works
- How to evaluate models with proper metrics
- Importance of threshold tuning

---

## 📌 Note

Make sure to download the `data.csv` file from Kaggle and place it in the same folder as the notebook before running.




