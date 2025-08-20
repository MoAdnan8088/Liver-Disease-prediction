# Liver Disease Prediction Model

## 📌 Overview

This project is a Machine Learning-based Liver Disease Prediction System that predicts whether a patient is likely to have liver disease based on their medical attributes.

The model is trained on patient health records and utilizes algorithms such as Logistic Regression, Decision Tree, Random Forest, and XGBoost to compare performance and improve accuracy.

## ⚙️ Features

Data preprocessing and cleaning for reliable results

Feature selection and analysis to identify key risk factors

Multiple machine learning algorithms implemented

Model evaluation using accuracy, precision, recall, and F1-score

Visualizations for better insights into data distribution and prediction outcomes

## 📂 Dataset

Source: Indian Liver Patient Dataset (ILPD) – UCI Repository (or specify your dataset source)

Attributes: Age, Gender, Total Bilirubin, Direct Bilirubin, Alkaline Phosphotase, SGPT, SGOT, Albumin, Prothrombin Time, etc.

Target:

1 → Patient has liver disease

0 → Patient does not have liver disease

## 🛠️ Technologies Used

Programming Language: Python

Libraries:

pandas, numpy → Data handling

matplotlib, seaborn → Data visualization

scikit-learn → Machine learning models & evaluation

xgboost → Gradient boosting classifier

## 🚀 Project Workflow

Data Collection – Load the liver dataset

Data Preprocessing – Handle missing values, encode categorical data, normalize features

Exploratory Data Analysis (EDA) – Visualize and analyze dataset patterns

Model Building – Train ML models (Logistic Regression, Decision Tree, Random Forest, XGBoost)

Model Evaluation – Compare Accuracy, Precision, Recall, F1-score, Confusion Matrix

Prediction – Use the trained model to predict liver disease on new data

## 📊 Results

Models were evaluated and compared.

Random Forest and XGBoost gave the best performance.

## ▶️ How to Run
# Clone the repository
git clone https://github.com/MoAdnann8088/liver-disease-prediction.git

# Navigate to the project folder
cd liver-disease-prediction

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook Liver_Disease_Prediction.ipynb

# OR run the Python script
python liver_prediction.py
