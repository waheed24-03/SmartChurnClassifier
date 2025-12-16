# 📊 ChurnShield: Predictive Analytics for Customer Retention

ChurnShield is an end-to-end machine learning solution designed to help businesses predict and reduce customer churn. Using advanced preprocessing techniques, SMOTE for class imbalance, and a Random Forest model, this project provides actionable insights into customer retention.

---


## 🚀 Project Overview

This project tackles the real-world challenge of predicting customer churn using historical customer interaction data. We apply a structured ML pipeline with the following key stages:

- 📌 Data Cleaning & Preprocessing
- 🔍 Exploratory Data Analysis (EDA)
- 🎯 Feature Engineering & One-Hot Encoding
- ⚖️ Resampling via SMOTE to fix class imbalance
- 🌲 Model Training with Random Forest Classifier
- 📈 Evaluation using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix
- 📉 Final metrics visualization for business presentation

---

## 🧠 Model Details
| Component               | Description                                  |
|------------------------|----------------------------------------------|
| **Model Used**         | Random Forest Classifier                     |
| **Imbalance Handling** | SMOTE (Synthetic Minority Over-sampling)     |
| **Accuracy Achieved**  | ~83.7%                                       |
| **ROC AUC**            | 0.90                                         |
| **Dataset Size**       | 1000 entries, expanded to 1592 post-SMOTE    |


---

## 📂 Folder Structure
churnshield/
│
├── data/               # Raw or cleaned datasets (optional)
├── notebooks/
│   └── churn_prediction.ipynb  # Main Jupyter notebook
├── images/             # Visualizations (e.g., confusion matrix)
├── README.md
├── requirements.txt






--- 

## 📈 Final Model Evaluation

- **Accuracy**: 83.7%
- **ROC AUC: 0.90
- **Precision/Recall**: Balanced post-SMOTE
- **Confusion Matrix**: Included
- **F1-Score**: Strong performance for both classes

---

## 📊 Technologies Used

- Python 
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---
``` bash
# Clone the repository
git clone https://github.com/your-username/churnshield.git
cd churnshield

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook
```




---

## 📎 Acknowledgements

- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)  
- [Imbalanced-learn (SMOTE) Documentation](https://imbalanced-learn.org/stable/)  
- [Forage Datasets](https://www.theforage.com/)

---



























