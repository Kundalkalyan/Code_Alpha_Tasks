Heart Disease Classification using Machine Learning
📌 Project Overview

This project builds a Heart Disease Classification System that predicts whether a person is at risk of heart disease based on medical attributes.

The model classifies patients into:

✅ No Heart Disease

❌ Heart Disease Present

The goal is to assist in early detection and improve healthcare decision-making using Machine Learning.

🧠 Problem Statement

Heart disease is one of the leading causes of death worldwide.

Using patient medical data such as age, blood pressure, cholesterol levels, and other health indicators, we train a Machine Learning model to predict:

“Is this patient likely to have heart disease?”

Early prediction can help in preventive treatment and save lives.

⚙️ Project Workflow
1️⃣ Data Collection

The dataset includes medical attributes such as:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol Level

Fasting Blood Sugar

Resting ECG Results

Maximum Heart Rate Achieved

Exercise Induced Angina

ST Depression

Slope of Peak Exercise ST Segment

2️⃣ Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling

Train-Test split

3️⃣ Model Training

Machine Learning models used:

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

4️⃣ Model Evaluation

Evaluation metrics:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

5️⃣ Model Saving (Optional)

The trained model can be saved using:

import joblib
joblib.dump(model, "heart_disease_model.pkl")

This allows deployment without retraining.

🛠️ Technologies Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Joblib

Jupyter Notebook
