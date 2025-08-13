# Customer Churn Prediction & Segmentation

## 📌 Project Overview
This project is part of the **DSBA Capstone** under the University of Texas at Austin program delivered by Great Learning.  
The objective is to perform data-driven analysis of customer churn, segment customers into distinct groups, and build predictive models to support retention strategies.

The project follows a structured workflow — from data exploration to preprocessing, segmentation, model building, and documentation — ensuring reproducibility and clarity.

---

## 📊 Dataset
- **Source:** Provided by Great Learning (DSBA Course – University of Texas at Austin)
- **Type:** Customer behavioral and demographic data
- **Size:** 11,260 rows × 19 columns
- **Target Variable:** `Churn` (1 = churned, 0 = retained)
- **Contents:**  
  - **Numerical features** – Tenure, Monthly Revenue, Cashback, Revenue Growth YoY, etc.  
  - **Categorical features** – Payment Method, Gender, Marital Status, Login Device, City Tier, etc.

---

## ⚙️ Workflow
1. **Data Import & Overview**  
   - Load dataset and review structure.
2. **Exploratory Data Analysis (EDA)**  
   - Missing value detection, descriptive statistics, univariate & bivariate analysis.
3. **Data Preprocessing**  
   - Imputation, outlier handling, feature engineering, encoding, and scaling.
4. **Clustering for Segmentation**  
   - K-means clustering with optimal K determined by Elbow Method.
5. **Class Balancing**  
   - Applied **SMOTE** to handle churn class imbalance.
6. **Model Training & Evaluation**  
   - Tested multiple ML algorithms; evaluated using precision, recall, F1, ROC-AUC.
7. **Documentation & Packaging**  
   - Report compilation, repository structuring, and licensing.

---


## 📚 References & Resources
- **Course Material:** DSBA Program (UT Austin × Great Learning)  
- **Python Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, imbalanced-learn  
- **General References:**  
  - Google Search for algorithm concepts  
  - Scikit-learn documentation ([https://scikit-learn.org](https://scikit-learn.org))

---

## 📜 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

**Author:** Sahid Ahmed  
**Program:** Data Science & Business Analytics (University of Texas at Austin × Great Learning)  
**Date:** March 2025
