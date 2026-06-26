# 🛍️ Shop Smart: Online Shoppers Purchasing Intention Prediction

##  Project Overview

This project uses a Decision Tree Classifier to predict whether an online visitor will make a purchase. It includes data preprocessing, feature engineering, model training, GridSearchCV for hyperparameter tuning, and model evaluation.

---

##  Objectives

* Analyze online shopper behavior.
* Predict customer purchase intention.
* Build a Decision Tree classification model.
* Optimize model performance using GridSearchCV.

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

##  Machine Learning Workflow

### 1. Data Cleaning

* Checked missing values
* Removed duplicates
* Converted Boolean values to integers

### 2. Exploratory Data Analysis (EDA)

* Examined data distribution
* Correlation analysis
* Feature visualization

### 3. Feature Engineering

* One-Hot Encoding
* Feature selection

### 4. Model Building

* Decision Tree Classifier
* Pipeline implementation
* Hyperparameter tuning with GridSearchCV

### 5. Model Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 📈 Model Performance

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **90.00%** |
| Precision | **67.66%** |
| F1-Score  | **64.94%** |

### Confusion Matrix

```
[[1971 108]
 [ 136 226]]
```

### Model Summary

The Decision Tree Classifier achieved an overall accuracy of **90.00%**. The model correctly identified **1,971 non-purchasing sessions** and **226 purchasing sessions**. While the model maintained good overall performance, there is still room to improve the detection of purchasing customers, making ensemble methods such as Random Forest or XGBoost promising future enhancements.


---

##  Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* One-Hot Encoding
* Pipeline
* Decision Tree Classification
* Hyperparameter Tuning
* GridSearchCV
* Model Evaluation
* Data Visualization

---

##  Future Improvements

* Random Forest Classifier
* XGBoost
* Feature Importance Analysis
* ROC Curve & AUC
* SHAP Explainability

---

##  Author

**Adhikari Sujan*

Aspiring Data Scientist | Machine Learning Enthusiast


