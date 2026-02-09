<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=260&section=header&text=ChurnShield&fontSize=80&animation=fadeIn&fontAlignY=38&desc=Customer%20Retention%20•%20Machine%20Learning%20•%20Predictive%20Analytics&descAlignY=55&descAlign=50" alt="ChurnShield Header" />

  <br />

  <p>
    <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit Learn" />
    <img src="https://img.shields.io/badge/Random_Forest-Classification-228B22?style=for-the-badge&logo=codacy&logoColor=white" alt="Random Forest" />
  </p>

  <h3>🛡️ Defending Revenue Through Data</h3>
  
  <p align="center">
    <i>"An end-to-end predictive analytics solution designed to identify at-risk customers and reduce churn using advanced ensemble methods."</i>
  </p>
</div>

---

## 🚀 Project Overview

**ChurnShield** tackles the critical business challenge of customer attrition. By analyzing historical interaction data, this project builds a robust machine learning pipeline to predict which customers are likely to leave. 

It goes beyond simple prediction by addressing real-world data issues like **class imbalance** (using SMOTE) and delivering interpretable metrics for business stakeholders.

---

## ⚙️ The ML Pipeline

This project follows a rigorous Data Science workflow:

- 📌 **Data Cleaning & Preprocessing**: Handling missing values and outliers.
- 🔍 **Exploratory Data Analysis (EDA)**: Uncovering patterns in customer behavior.
- 🎯 **Feature Engineering**: One-Hot Encoding and feature scaling.
- ⚖️ **Imbalance Handling**: Applying **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset.
- 🌲 **Model Training**: Utilizing the **Random Forest Classifier** for robust predictions.
- 📈 **Evaluation**: Optimized for Recall and F1-Score to minimize false negatives.

---

## 🧠 Model Performance

The model was rigorously tested, and the dataset was expanded from **1000 to 1592 entries** post-SMOTE to ensure fair training.

| Metric | Value | Status |
| :--- | :--- | :--- |
| **Accuracy** | **83.7%** | 🟢 High |
| **ROC-AUC Score** | **0.90** | 🟢 Excellent |
| **F1-Score** | **Balanced** | 🟢 Strong |
| **Technique** | **SMOTE + Random Forest** | 🛡️ Robust |

---

## 🛠 Technology Stack

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/-Python-black?style=flat-square&logo=python) | Core programming |
| **ML Core** | ![Scikit-Learn](https://img.shields.io/badge/-Scikit_Learn-black?style=flat-square&logo=scikit-learn) | Classification Algorithms |
| **Data Ops** | ![Pandas](https://img.shields.io/badge/-Pandas-black?style=flat-square&logo=pandas) | Data Manipulation |
| **Sampling** | ![Imbalanced-Learn](https://img.shields.io/badge/-Imbalanced_Learn-black?style=flat-square) | SMOTE Implementation |
| **Viz** | ![Matplotlib](https://img.shields.io/badge/-Matplotlib-black?style=flat-square&logo=matplotlib) | Data Visualization |

---

## 📂 Project Structure

```bash
churnshield/
│
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter notebooks for EDA and Modeling
│   └── churn_prediction.ipynb
├── images/               # Confusion matrices and ROC curves
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```
## ⚙️ Local Setup

Follow these steps to replicate the analysis locally:

 1. Clone the repository
git clone https://github.com/Syed-Waheed/churnshield.git

 2. Navigate to the directory
cd churnshield

 3. Install dependencies
pip install -r requirements.txt

 4. Launch Jupyter Notebook
jupyter notebook

---

## 📎 Acknowledgements

Special thanks to the open-source community and resources that made this possible:

- Scikit-learn Documentation
- Imbalanced-learn (SMOTE)
- Forage for dataset inspiration

---

## 👤 Author

<div align="left">
  <img src="https://github.com/Syed-Waheed.png" width="100" align="left" style="margin-right: 20px; border-radius: 50%;" alt="Syed Abdul Waheed" />

  <strong>Syed Abdul Waheed</strong><br/>
  <em>Data Science Enthusiast | Python Developer | Automation Explorer</em>

  Focused on building concepts rather than memorizing syntax. Actively working on strengthening practical implementation skills in AI & ML.

  <br /><br />

  <a href="https://www.linkedin.com/in/syed-abdul-waheed/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://github.com/Syed-Waheed">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github" />
  </a>
</div>

<br clear="left"/>


---





