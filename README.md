# ITAI1371_Final_ML_Project_AlfredoGarza

# Final Machine Learning Project – Income Prediction

**Student:** Alfredo Garza  
**Course:** ITAI 1371 – Intro to Machine Learning  

---

## 📌 Project Overview

This project uses machine learning to predict whether an individual earns more than $50,000 per year based on demographic and employment-related data.

The problem is treated as a **binary classification task**, where:

- 0 → Income ≤ 50K  
- 1 → Income > 50K  

---

## 📊 Dataset

The dataset used is the **Adult Census Income dataset**, originally from the UCI Machine Learning Repository and commonly available on Kaggle.

It contains approximately 48,000 records with features such as:
- Age  
- Education  
- Occupation  
- Hours worked per week  
- Capital gain/loss  

👉 Dataset source (Kaggle):  
https://www.kaggle.com/datasets/uciml/adult-census-income

---

## 🧹 Data Preprocessing

The dataset was cleaned and prepared using the following steps:

- Replaced missing values ("?") with NaN  
- Filled missing values using mean (numerical) and mode (categorical)  
- Converted categorical variables using one-hot encoding  
- Encoded the target variable into binary format (0/1)  

The data was split into:
- 70% Training  
- 15% Validation  
- 15% Test  

---

## 🤖 Models Used

The following machine learning models were trained and evaluated:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier  
- K-Nearest Neighbors (KNN)  
- Support Vector Classifier (SVC)  

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

F1-score was used as the primary metric for model comparison.

---

## 🏆 Results

- **Best Model:** Gradient Boosting  
- **Reason:** Highest F1-score and ROC-AUC with strong generalization  

Additional observations:
- Voting Ensemble performed well but did not outperform Gradient Boosting  
- Random Forest also showed strong performance  
- KNN, SVC, and Naive Bayes performed poorly on this dataset  

---

## 🔗 Files Included

- `Final_Alfredo_Garza_ITAI1371.ipynb` → Main notebook  
- `adult_income.csv` → Dataset  
- `FinalReport_AlfredoGarza_ITAI1371.pdf` → Project report  
- `ModelComparison_AlfredoGarza_ITAI1371.pdf` → Model comparison table  
- `Presentation_AlfredoGarza_ITAI1371.pdf` → Slide deck  

---

## ▶️ How to Run

1. Open the Jupyter Notebook:
