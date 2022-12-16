# Stroke Analysis
This repository is a final project for DATA 5100 class: Introduction to Data Science from Seattle University. This project requires student to perform analysis and machine learning to real life data. 

In this project, the author tries to describe characteristics of a person who have stroke based on their health indicators and conditions. Then using machine learning to predict the probability of a person who have stroke.

# Data description:
This data include health indicators of 5110 individuals like their age, average glucose level, bmi, smoking status; whether they have hypertension, heart disease or stroke. Along with that are some characteristics like Gender, Work Type, Residence Type, Marriage status. 

We want to predict the probability of people who get stroke from this dataset, which make 'stroke' our dependent variables with other 10 independeneces (after droping unessasary columns).

# Analytical Approach:
This dataset include our independent and dependent variables, with the dependent one being binary, so we will apply supervised learning with classification problem.
For this type of problem, Decision Tree models and Logistic Regression will be applied. 

More sophisticated tree-based like Random Forest and XGBoost might be used.
Since the data is heavily imbalanced and the baseline model might be bias toward the non-stroke class, we will try to mix in resampling methods and balanced weight class parameter.

# Data Source:
The data is found here: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

_ Limitation: The original collected sources are kept unknown and only for practice purposes only.

_ Assumption: Without clear timestamp of when the conditions are collected, we will use this data under some assumptions: The age column presents the timestamp when the person got stroke for the first time, and all other conditions are underlying conditions.

# Solution technologies:
We will first use pandas, seaborn and matplotlib packages for data cleaning, exploratory analysis and visualization. Finally, Scikit_learn library will be applied to train and predict the data to predict how many people whether get stroke or not, and the module library of confusion matrix (confusion_matrix, classification_report) to calculate the accuracy of the model.

