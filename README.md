# Heart Disease Prediction using Machine Learning
>> Project Overview

This project focuses on predicting the presence of heart disease using machine learning classification algorithms. The system analyzes clinical and demographic patient data to determine whether a person is at risk of heart disease.

The objective of this project is to build a reliable and data-driven predictive model that can assist in early detection and medical decision-making.

>> Dataset Information

Dataset Source: Kaggle – Link: [https://www.kaggle.com/....](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
The dataset contains clinical attributes such as:

1.Age
2.Sex
3.Chest Pain Type
4.Resting Blood Pressure
5.Cholesterol
6.Maximum Heart Rate
7.ST Slope
8.Exercise Induced Angina
And other medical parameters

The dataset is used for binary classification:

0 → No Heart Disease

1 → Heart Disease Present

>> Technologies Used

Python 3.14
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn

>> Machine Learning Algorithms Implemented

The following classification algorithms were implemented and compared:

Logistic Regression
Support Vector Machine (SVM)
Decision Tree Classifier
Random Forest Classifier
Hyperparameter tuning was performed using GridSearchCV for improved performance.

>> Model Performance
Algorithm	Performance
Logistic Regression	86.96% Accuracy
SVM (Linear Kernel)	86.33% F1-Score
Decision Tree	86.41% Accuracy
Random Forest	85.87% Accuracy

--Logistic Regression achieved the highest accuracy on the test dataset.--

>> Project Workflow

Data Collection (Kaggle Dataset)

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Encoding Categorical Variables

Train-Test Split

Model Training

Hyperparameter Tuning

Model Evaluation

Performance Comparison

>> Future Scope

Deployment as a web application using Streamlit or Flask

Integration with hospital systems for real-time prediction

Implementation of advanced models like XGBoost

Addition of Explainable AI (XAI) methods

📂 Repository Structure
Heart-Disease-Prediction-ML/
│
├── Heart_Disease_Predictor.ipynb
├── heart.csv
├── images/
│   ├── correlation_plot.png
└── README.md

👩‍💻 Author
ANUSHKA ROY
B.Tech – Computer Science
Email: roy916968@gmail.com

