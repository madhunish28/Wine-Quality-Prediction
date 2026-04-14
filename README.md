# Wine Quality Prediction

## 📌 Project Overview
This project predicts whether a wine is **Good or Bad** using machine learning.

## Problem Statement
Classify wine quality based on physicochemical properties.

## Tools Used
- Python
- Pandas
- Scikit-learn
- Google Colab

## Model Used
- Logistic Regression

## Steps Performed
1. Data Cleaning
2. Feature Selection
3. Converted quality into binary classification
4. Train-Test Split
5. Model Training
6. Model Evaluation

## Results
- Accuracy: **89%**

# Key Insights

## Data Insights

1. Most wines are classified as **bad (0)** compared to good (1), indicating an imbalanced dataset.

2. Features like **alcohol, sulphates, and citric acid** show positive correlation with wine quality.

3. Features like **volatile acidity** show negative correlation with quality — higher acidity often reduces quality.

4. Majority of wines fall in mid-range chemical composition, with fewer extreme values.

---

## Model Insights

1. Logistic Regression model achieved an accuracy of **89%**, indicating strong predictive performance.

2. The model is better at predicting the majority class (bad wine), due to class imbalance.

3. Feature scaling improved model convergence and performance.

---

## Business Insights

1. Increasing **alcohol content and sulphates** may improve wine quality.

2. Controlling **volatile acidity** is important for producing high-quality wine.

3. The model can be used by wine producers to **predict quality before production**, saving cost and improving consistency.

---

## Conclusion

The model successfully classifies wine quality with high accuracy and provides useful insights into factors affecting wine quality.

## Files
- `WineQuality.ipynb` → Full project code

---
