# IBM HR Analytics Employee Attrition & Performance Prediction

## Author Details

**Author:** Gargee Singh

**Registration Number:** 23BCE11449

**Application Number:** IN26011964

**Batch Number:** 1A (1:00–3:00 PM)

**Email ID:** gargee.23bce11449@vitbhopal.ac.in

**Course:** B.Tech Computer Science and Engineering (CSE)

**Assignment:** Assignment 5 – Decision Tree & Random Forest Classification

---

# Project Overview

Employee attrition is one of the major challenges faced by organizations as it affects productivity, increases recruitment costs, and impacts overall business performance. Predicting employee attrition enables organizations to identify employees who are likely to leave and implement effective retention strategies.

This project uses the **IBM HR Analytics Employee Attrition & Performance** dataset to develop and compare two supervised machine learning models: **Decision Tree Classifier** and **Random Forest Classifier**. The dataset is preprocessed by checking for missing values, removing unnecessary columns, encoding categorical variables, and splitting the data into training and testing sets. Both models are trained and evaluated using standard classification metrics such as Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and Feature Importance. The project concludes by comparing the performance of both models and identifying the most suitable algorithm for employee attrition prediction.

---

# Objective

The objective of this project is to predict whether an employee is likely to leave the organization (Attrition) using Machine Learning classification techniques. Two supervised learning algorithms—**Decision Tree** and **Random Forest**—are implemented, trained, and evaluated to determine which model provides better prediction performance. The project also analyzes the most important factors contributing to employee attrition.

---

# Dataset Link

**Dataset Name:**

IBM HR Analytics Employee Attrition & Performance

**Kaggle Link:**

https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

---

# Libraries Used

The following Python libraries were used in this project:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Scikit-learn Modules

- train_test_split
- LabelEncoder
- DecisionTreeClassifier
- RandomForestClassifier
- accuracy_score
- precision_score
- recall_score
- f1_score
- confusion_matrix
- classification_report

---

# Methodology

The project was completed using the following steps:

1. Imported the required Python libraries.
2. Loaded the IBM HR Analytics dataset using Pandas.
3. Displayed the first five records of the dataset.
4. Identified numerical features, categorical features, and the target variable.
5. Displayed dataset information and summary statistics.
6. Checked the dataset for missing values.
7. Removed the unnecessary **EmployeeNumber** column.
8. Encoded all categorical features using **LabelEncoder**.
9. Split the dataset into **80% training data** and **20% testing data**.
10. Developed a **Decision Tree Classifier** model.
11. Developed a **Random Forest Classifier** with **100 estimators**.
12. Predicted employee attrition using both models.
13. Evaluated model performance using:
    - Accuracy
    - Precision
    - Recall
    - F1-Score
    - Classification Report
    - Confusion Matrix
14. Generated the **Feature Importance** graph for the Random Forest model.
15. Compared the performance of both classification models.

---

# Results

The performance of both models was evaluated using multiple classification metrics.

### Evaluation Metrics

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

### Outcome

- Both models successfully classified employee attrition.
- The **Random Forest Classifier** achieved better overall performance than the Decision Tree Classifier.
- Random Forest produced higher Accuracy, Precision, Recall, and F1-Score.
- Feature Importance analysis revealed that variables such as **OverTime**, **MonthlyIncome**, **Age**, **TotalWorkingYears**, and **JobLevel** had the greatest influence on employee attrition prediction.

---

# Model Comparison

| Model | Advantages | Limitations |
|-------|------------|-------------|
| **Decision Tree** | Easy to understand, simple to visualize, fast training, interpretable | Can easily overfit the training data and produce unstable predictions |
| **Random Forest** | Higher accuracy, reduces overfitting, better generalization, robust to noisy data | Requires more computational resources and longer training time |

### Comparison Summary

- Decision Tree is simple and interpretable but prone to overfitting.
- Random Forest combines multiple decision trees to improve prediction accuracy.
- Random Forest provides better generalization on unseen data.
- Overall, Random Forest outperformed the Decision Tree in Accuracy, Precision, Recall, and F1-Score.

---

# Conclusion

This project demonstrates the application of machine learning techniques for predicting employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. Both the Decision Tree and Random Forest classifiers were successfully trained and evaluated after appropriate data preprocessing and feature encoding. The models were assessed using Accuracy, Precision, Recall, F1-Score, Classification Report, Confusion Matrix, and Feature Importance.

Among the two models, the **Random Forest Classifier** performed better by achieving higher prediction accuracy and better overall classification metrics. This is because Random Forest combines the predictions of multiple decision trees, reducing overfitting and improving generalization. The feature importance analysis also highlighted the key factors affecting employee attrition, providing valuable insights for organizations.

Although the Decision Tree algorithm is easy to understand and visualize, it is more susceptible to overfitting. On the other hand, Random Forest requires more computational resources and longer training time. Overall, Random Forest proved to be the more reliable and effective model for employee attrition prediction.

---

# Repository Contents

```
Assignment-5.ipynb
README.md
WA_Fn-UseC_-HR-Employee-Attrition.csv
```

---
