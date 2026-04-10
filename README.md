# Breast Cancer Analysis - Data Analysis and Prediction of Breast Cancer

## project introduction

This project uses the **Wisconsin Breast Cancer dataset ** of Kaggle to conduct an exploratory analysis of the nuclear characteristics of breast tumors and construct a ** random forest classification model ** to predict whether the tumor is Benign or Malignant.

Through feature importance analysis, the key indicators that have the greatest impact on diagnosis are identified to provide data support for assisting medical decision-making.

##  data source

- ** Dataset Name ** : Breast Cancer Wisconsin (Diagnostic) Data Set
- source of * * * * : [Kaggle - UCI Machine Learning Repository] (https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- ** Data Size ** : 569 samples, 32 features (radius, texture, perimeter, area, smoothness, etc. of the cell nucleus)

##  project process

Steps: Contents
|------|------|
1. Data Loading and Exploration (View shapes, Statistical summaries, Missing Value checks
2. Data cleaning (delete the useless 'Unnamed: 32' column, label code M/B → 1/0)
Visualization Analysis (Correlation heat map, distribution of target variables
4. Training and Evaluation of Random Forest Models
Feature Importance Analysis (Identifying the most critical influencing factors

##  model effect

"Indicator: Score
|------|------|
Accuracy rate: 96.49%
Accuracy rate (benign) : 0.96
Accuracy rate (malignancy) : 0.98
Recall rate (benign) : 0.99
Recall rate (malignant) : 0.93

&gt;  The model performed well on the test set and was capable of effectively distinguishing between benign and malignant tumors.

##  Most important features (Top 5)

Sort by the feature importance of the random forest:

Ranking: Feature Name: Importance Score
|------|----------|------------|
1 area_worst (worst area) 0.154
2: concave points_worst (worst concave point) : 0.145
The concave points_mean (average concave point) is 0.106
4 radius_worst (worst radius) 0.078
5: concavity_mean (average concavity) : 0.068

&gt;  ** Conclusion ** : The morphological characteristics of the cell nucleus, such as ** area, concave points, and radius **, have the greatest influence on determining the benign or malignant nature of tumors.

##  technology used

- **Python** : Pandas, NumPy, Matplotlib, Seaborn
- **Scikit-learn** : RandomForestClassifier, train_test_split, accuracy_score, classification_report
- ** Environment ** : Jupyter Notebook

How does  work

1. Clone repository to local
```bash
git clone https://github.com/11zhouyuhan/breast-cancer-analysis.git
