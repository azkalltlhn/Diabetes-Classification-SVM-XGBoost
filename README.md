# Diabetes Disease Classification Using Support Vector Machine (SVM) and Extreme Gradient Boosting (XGBoost)

# Introduction
Diabetes mellitus is a chronic disease with a rising global prevalence, potentially leading to serious complications such as heart disease and stroke. Early diagnosis is crucial, but conventional methods like blood sugar tests are often insufficiently sensitive in the early stages.

# Methods Used
1. Support Vector Machine (SVM): Identifies the optimal hyperplane to separate data classes.
2. XGBoost: A decision tree-based algorithm that enhances prediction accuracy.

# Dataset
The "Diabetes Prediction Dataset" from Kaggle contains patient health information used to predict diabetes likelihood. The dataset consists of 100,000 rows and 9 key features, including age, gender, BMI, hypertension, heart disease, and blood glucose levels.

# Data Processing
The data is processed using Google Colab with libraries such as pandas, numpy, matplotlib, and seaborn. The main steps include:
1. Statistical Analysis: Descriptive analysis to understand data characteristics.
2. Data Cleaning: Removing duplicates to maintain dataset integrity.
3. Data Exploration: Visualizing distributions and relationships between variables.
4. Data Balancing: Applying sampling methods to ensure balanced class distribution.
5. Feature Transformation: Converting categorical features into numerical format using LabelEncoder.

# Machine Learning Model
SVM and XGBoost models are utilized to build a diabetes prediction system, with model evaluation conducted to assess classification performance.

This research aims to enhance the accuracy of early diabetes detection and provide a more reliable diagnostic tool for healthcare professionals.
