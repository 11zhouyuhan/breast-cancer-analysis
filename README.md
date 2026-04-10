# Breast Cancer Analysis - Data Analysis and Prediction of Breast Cancer

Project Introduction

This project uses the Wisconsin Breast Cancer dataset of Kaggle to conduct an exploratory analysis of the nuclear characteristics of breast tumors and construct a random forest classification model to predict whether the tumors are benign or malignant. Through feature importance analysis, the key indicators that have the greatest impact on diagnosis are identified to provide data support for assisting medical decision-making.

Data source

Dataset Name: Breast Cancer Wisconsin (Diagnostic) Data Set
Source: Kaggle - UCI Machine Learning Repository
Data scale: 569 samples, 32 features (radius, texture, perimeter, area, smoothness, etc. of the cell nucleus)

Project process

Step 1: Data Loading and Exploration (Viewing shapes, statistical summaries, missing value checks)
Step 2: Data cleaning (Delete the useless Unnamed: 32 columns and convert the tag code M/B to 1/0)
Step 3: Visual Analysis (Correlation heat Map, Distribution of Target variables)
Step Four: Training and Evaluation of the Random Forest model
Step 5: Feature Importance Analysis (Identify the most critical influencing factors)

Model effect

Accuracy rate: 96.49%
Accuracy rate for benign tumors: 0.96
The accuracy rate of malignant tumors: 0.98
Benign tumor recall rate: 0.99
Recall rate of malignant tumors: 0.93

The model performed well on the test set and was capable of effectively distinguishing between benign and malignant tumors.

The most important features (Top5

Sort by the feature importance of the random forest:

First place: area_worst (worst area), importance score 0.154
Second place: concave points_worst (worst concave point), with an importance score of 0.145
Third place: concave points_mean (average concave point), importance score 0.106
4th place: radius_worst (Worst radius), importance score 0.078
5th place: concavity_mean (average concavity), importance score 0.068

Conclusion: The morphological characteristics of the cell nucleus, such as its area, depressions, and radius, have the greatest influence on determining the benign or malignant nature of tumors.

The technology used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn (RandomForestClassifier, train_test_split, accuracy_score, classification_report)
Environment: Jupyter Notebook

How to operate

1. Clone repository to local
git clone https://github.com/11zhouyuhan/breast-cancer-analysis.git

2. Install dependent packages
pip install pandas numpy matplotlib seaborn scikit-learn

3. Start Jupyter Notebook, open breast cancer analysis.ipynb, and run all cells in sequence.

Document Description

breast cancer analysis.ipynb: Complete data analysis and modeling code
README.md: Project Description Document

Project value

Postgraduate entrance examination or recommendation for postgraduate study re-examination: Prove the practical ability of data analysis and machine learning
Resume: Demonstrate project experience in Python, Pandas, and Scikit-learn
Introduction to Medical AI: Understanding the Application of Feature Engineering and Model Interpretation in Medical Scenarios

Contact information

GitHub: 11zhouyuhan
Projects link: https://github.com/11zhouyuhan/breast-cancer-analysis
