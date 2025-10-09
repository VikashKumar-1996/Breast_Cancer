# Brest_Cancer
#  Breast Cancer Classification using Logistic Regression and Random Forest

##  Overview
This project applies **Machine Learning algorithms** — Logistic Regression and Random Forest — to classify whether a tumor is **malignant** or **benign** using the **Breast Cancer Wisconsin dataset** from `sklearn.datasets`.

The workflow includes:
- Data loading and exploration  
- Preprocessing  
- Model training (Logistic Regression & Random Forest)  
- Evaluation and comparison  

---

##  Dataset
Dataset used: **Breast Cancer Wisconsin (Diagnostic)**, available via scikit-learn.

```python
from sklearn.datasets import load_breast_cancer
data = load_breast_cancer()
