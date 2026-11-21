# Diabetes Prediction Using Machine Learning

## Project Overview

Diabetes is a chronic disease that requires early detection and appropriate medical management. This project develops an end-to-end machine learning pipeline to predict diabetes using patient-related clinical and demographic data.

The project explores data preprocessing, exploratory data analysis, feature handling, model training, and evaluation to investigate the performance of different machine learning classification algorithms in predicting diabetes outcomes.

## Dataset

The project uses the **Pima Indians Diabetes Dataset**, containing clinical and demographic features used to predict diabetes status.

The dataset includes the following predictor variables:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable:** `Outcome`
- `0` — Non-diabetic
- `1` — Diabetic

The dataset contains 768 observations and 8 predictor features.

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Dataset inspection and statistical analysis
- Target variable distribution analysis
- Identification of physiologically invalid zero values
- Feature correlation analysis
- Comparison of clinical feature distributions across outcome groups

### 2. Data Preprocessing
- Identification of invalid zero values in selected clinical features
- Treatment of invalid values as missing data
- Median imputation for missing values
- Feature scaling using StandardScaler
- Stratified splitting into training, validation, and test sets

### 3. Model Development

Three machine learning classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest

### 4. Model Evaluation

Models were evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-score

Validation data was used for model comparison and selection, while the test set was reserved for final evaluation.

## Model Comparison

The performance of the three models was compared across validation and test datasets to assess their predictive performance and generalization.

Random Forest was selected as the final model based on its overall validation performance and its performance consistency across the validation and test sets.

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Contents

- `end-to-end-medical-ml-capstone-diabetes-prediction.ipynb` — Complete project notebook containing data exploration, preprocessing, model training, comparison, and evaluation.

## Disclaimer

This project is developed for educational and research purposes. The models are not intended to replace professional medical diagnosis or clinical decision-making.


**Author:** Alaa Nasr  
Dentist | MSc Student in Artificial Intelligence in Healthcare
