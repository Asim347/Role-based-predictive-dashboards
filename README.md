# AI-Powered Role-Based Dashboard System for Personalized Business Intelligence

> **Status:** Undergraduate Research Paper | IMSciences, Peshawar | [cite_start]Completed – Pending Publication [cite: 53]
> **Supervisor:** Mr. Ali Haider, IMSciences | [cite_start]**Ethics Approval:** IMSC-REC-2024-047 [cite: 63]

---

## 📌 Abstract / Project Overview
[cite_start]This repository contains the end-to-end AI system designed to automatically generate personalized, role-aware interactive dashboards from any structured CSV dataset without requiring domain-specific configuration[cite: 54]. [cite_start]By combining machine learning classification with an adaptive visualization engine[cite: 58], the system automatically translates raw data into tailored, high-impact business insights.

---

## 🚀 Key Performance & Usability Metrics

### 🤖 Machine Learning Performance
* [cite_start]**Top Classifier:** XGBoost outperformed Random Forest, SVM, and Logistic Regression after a 5-fold Stratified GridSearchCV optimization[cite: 56, 57].
* [cite_start]**Classification Accuracy:** Achieved a top **ROC-AUC score of 0.895**[cite: 57].
* [cite_start]**Feature Retention:** Recursive Feature Elimination (RFE) successfully streamlined data processing at **~75% feature retention**[cite: 55].

### 👥 Human-Computer Interaction & Usability Results
[cite_start]Based on a Monte Carlo usability simulation ($n=40$), the system demonstrated statistically significant advantages over traditional static dashboards ($p < 0.001$, Cohen's $d > 1.78$)[cite: 61]:
* [cite_start]**System Usability Scale (SUS):** Scored **82.4**, placing it firmly in the **'Excellent'** category[cite: 61].
* [cite_start]**Efficiency:** Achieved a **38% reduction in time-to-insight** for users[cite: 61].
* [cite_start]**Cognitive Load:** Reduced mental fatigue by **40.5%** based on NASA-TLX workload metrics[cite: 61].
* [cite_start]**Expert Validation:** A 3-domain-expert validation confirmed a high inter-rater agreement taxonomy of **$\kappa = 0.87$**[cite: 62].

---

## 🛠️ System Architecture & Data Pipeline
The core application is engineered around a robust 7-step pipeline:
1. [cite_start]**Data Preprocessing:** Handled via median/mode imputation, deduplication, Label Encoding, and Min-Max Scaling[cite: 55].
2. [cite_start]**Feature Engineering:** Automated RFE combined with an 80:20 stratified train/test split[cite: 55].
3. [cite_start]**ML Classification Layer:** Predictive model matching data profiles to optimal organizational roles[cite: 54, 59].
4. [cite_start]**Adaptive UI Engine:** Built using **Plotly Dash** to dynamically render multi-tab, interactive components and charts based on predicted KPIs[cite: 58].

### Tech Stack
* [cite_start]**Languages & Core:** Python, Pandas, NumPy, SciPy [cite: 64]
* [cite_start]**Machine Learning:** Scikit-learn, XGBoost [cite: 64]
* [cite_start]**Dashboard & UI:** Plotly Dash [cite: 64]

---

## ⚙️ How to Run the Application Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Asim347/YOUR-REPO-NAME.git](https://github.com/Asim347/YOUR-REPO-NAME.git)
   cd YOUR-REPO-NAME

2. pip install -r requirements.txt
3. python app.py
