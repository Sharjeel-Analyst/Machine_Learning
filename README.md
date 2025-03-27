# Machine_Learning
Random Forest Algorithm working on heart attack risk calculation

# Dataset Summary
This dataset contains 8,763 records with 26 attributes, primarily focused on cardiovascular health factors. The target variable for classification is "Heart Attack Risk", which is binary (0 = No Risk, 1 = High Risk).

# Dependences::
pandas
numpy
matplotlib
seaborn
imblearn
sklearn
# Why Use Random Forest for Heart Attack Prediction?
•	Handles High-Dimensional Data: The dataset has 25+ features, and Random Forest is good at selecting the most important ones.
•	Reduces Overfitting: Unlike individual decision trees, it generalizes well to new data.
•	Feature Importance Ranking: It helps identify the most critical risk factors (e.g., Cholesterol, Smoking, Family History).
•	Works well with Missing Data: It can handle missing values by averaging results from multiple trees.
# Feature Importance in Heart Attack Prediction:
  Random Forest assigns importance scores to each feature. Likely top predictors of heart attack risk from this dataset:
•	Cholesterol Levels
•	Blood Pressure (Systolic/Diastolic)
•	BMI (Obesity Indicator)
•	Smoking & Alcohol Consumption
•	Family History of Heart Disease
•	Previous Heart Problems
