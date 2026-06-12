# Colorectal-Cancer-Risk-Classification
Project Overview:

This project views Colorectal cancer risk prediction in the lens of a binary risk classification machine learning problem. A logistic regression model is trained to predict whether an individual belongs to the at risk or not at risk category by using demographic, lifestyle, family history, and dietary intake features. 

Technology and Python Packages Used:

- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Dataset:

The dataset was synthetically generated and taken from Kaggle. 

Colorectal Cancer Dietary and Lifestyle Dataset
https://www.kaggle.com/datasets/ziya07/colorectal-cancer-dietary-and-lifestyle-dataset

Results and evaluation:

Prior to performing any machine learning or visualization, additional steps were taken to verify that the dataset is free from duplicate records, missing values, and incorrect values. Matplotlib was used to create visualizations to better understand the distribution of our features.  

In this project, cross validation was implemented with k = 5 to evaluate the performance of our model. During each fold, a logistic regression model  was trained on 4 folds and then validated on the remaining fold. This process was continued until each fold was used for validation exactly once. Model performance was evaluated for each fold using  recall, precision, accuracy,  f1 score, and ROC AUC. Each of these metrics were recorded for each fold and then averaged across 5 folds. 

Average Results obtained accross 5 folds:

Average Accuracy: 0.807
Average Recall: 0.904
Average Precision: 0.439
F1 Score: 0.591
AUC: 0.846

**** This project/model is just for educational purposes and can’t be used for medical screening or anything medical/health related. ***

