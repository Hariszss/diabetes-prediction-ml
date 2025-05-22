# Diabetes Prediction Using Machine Learning

##  Project Overview

This project focuses on predicting whether a patient has diabetes based on diagnostic medical measurements. It uses the **Pima Indians Diabetes Dataset**, which contains health-related data for female patients of at least 21 years of age from the Pima Indian population.

The goal is to apply various machine learning algorithms to classify patients accurately and understand the performance of each model.

## Dataset

- **Source**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Observations**: 768
- **Features**: 8 input features and 1 output label (`Outcome`)
- **Target**: Binary classification (0 = No diabetes, 1 = Diabetes)

| Feature               | Description                             |
|------------------------|-----------------------------------------|
| Pregnancies           | Number of times pregnant                |
| Glucose               | Plasma glucose concentration            |
| BloodPressure         | Diastolic blood pressure (mm Hg)        |
| SkinThickness         | Triceps skin fold thickness (mm)        |
| Insulin               | 2-Hour serum insulin (mu U/ml)          |
| BMI                   | Body mass index                         |
| DiabetesPedigreeFunction | Diabetes pedigree function             |
| Age                   | Age (years)                             |

##  Methodology

1. **Data Preprocessing**
   - Handling zero values as missing data
   - Feature scaling and normalization
   - Train-test split

2. **Exploratory Data Analysis (EDA)** _(to be expanded)_
   - Correlation analysis
   - Distribution plots

3. **Model Training**
   - Logistic Regression
   - Random Forest Classifier
   - (More models can be added in future iterations)

4. **Model Evaluation**
   - Accuracy score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)

## Results

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | 74.6%    |
| Support Vector Machine | 76.6%    |
| Random Forest          | 72.0%    |

## 📂 Project Structure
diabetes-prediction-ml/
│
├── data/ # Dataset files (optional, or link to Kaggle)
├── notebooks/ # Jupyter Notebooks for analysis
├── scripts/ # Python scripts for preprocessing/training
├── README.md # Project documentation
└── requirements.txt # Python dependencies

