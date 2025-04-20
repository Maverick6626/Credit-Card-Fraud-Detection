## Dataset

- **Source:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
---

## Key Insights

- Highly imbalanced dataset, fraud is rare
- High-amount transactions are more likely to be fraud
- No missing values, but had duplicates which were dropped
- V1 to V28 are transformed using PCA
- Data spans two days

---

## Techniques Used to Handle Imbalance

- **Undersampling:** Balancing classes by reducing majority class
- **Class Weights Balancing:** Adjusted in logistic regression and XGBoost Classifier to handle imbalance
- **SMOTE:** Creating dummy data for balanced training

---

## Algorithms Used

- **Logistic Regression**
- **XGBoost Classifier**

---

## Evaluation Metrics

- Accuracy
- ROC AUC Score

