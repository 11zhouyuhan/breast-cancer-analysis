# Breast Cancer Analysis - Data Analysis and Prediction of Breast Cancer

## project introduction
Using the Wisconsin Breast Cancer dataset of Kaggle, the nuclear characteristics of breast tumors were analyzed, and a  random forest classification model  was constructed to predict whether the tumor was benign or malignant.

## data source
[Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

##  project process
1. Data loading and exploration (Viewing shapes, statistical summaries, missing value checks
2. Data cleaning (deleting unnecessary columns and label codes)
3. Visual Analysis (Correlation heat map, Feature Distribution)
4. Training and Evaluation of Random Forest Models
5. Feature Importance analysis

## model effect
- Accuracy rate: 96.5%
- ** Accuracy ** : 0.96
- Recall rate: 0.95

&gt;  Please fill in the accuracy rate you actually achieved.

## technology used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (RandomForestClassifier, train_test_split)

How does work
1. Clone repository
2. install dependencies: 'pip install pandas numpy matplotlib seaborn scikit-learn'
3. Run Jupyter Notebook

Conclusion: 
The morphological characteristics of the cell nucleus, such as its radius, area and circumference, have the greatest influence on determining the benign or malignant nature of tumors. The model can assist doctors in conducting preliminary screening.
