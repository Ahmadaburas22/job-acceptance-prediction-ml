# job-acceptance-prediction-ml
Machine Learning project for predicting job acceptance using data preprocessing, feature engineering, and classification models including Random Forest, AdaBoost, Logistic Regression, and KNN.

# Job Acceptance Prediction using Machine Learning

## Overview

This project focuses on predicting whether a candidate will be accepted for a job position based on demographic, educational, professional, and technical background information.

The project covers the complete machine learning workflow, including:

* Exploratory Data Analysis (EDA)
* Data Cleaning and Preprocessing
* Feature Engineering
* Missing Value Handling
* Outlier Detection
* Feature Selection
* Model Training and Evaluation
* Performance Comparison

Several classification algorithms were implemented and compared to identify the most effective model for this prediction task.

---

## Dataset

The dataset contains candidate-related information, including:

* Years of experience
* Previous salary
* Education level
* Technical skills
* Development background
* Country
* Employment history
* Additional demographic and professional features

The target variable is:

* **Job Acceptance** (Accepted / Not Accepted)

---

## Data Preprocessing

The preprocessing pipeline included:

### Missing Values Handling

Different strategies were applied depending on feature type:

* Statistical imputation
* Distribution-based sampling
* Domain-driven imputation
* Category grouping

### Outlier Detection

Outliers were identified using the Interquartile Range (IQR) method.

### Feature Engineering

* Categorical encoding
* Technology stack grouping
* Country-to-continent mapping
* One-Hot Encoding

### Feature Selection

Mutual Information (MI) was used to identify the most informative features and reduce unnecessary dimensionality.

---

## Models Evaluated

The following machine learning models were trained and compared:

1. Random Forest Classifier
2. AdaBoost Classifier
3. Logistic Regression
4. K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed to improve generalization performance and reduce overfitting.

---

## Evaluation Metrics

Models were evaluated using:

* ROC Curve
* AUC Score
* Cross Validation
* Confusion Matrix
* Accuracy
* Precision

---

## Results

Random Forest achieved the best overall performance and was selected as the final model.

Key findings:

* Technical skills and experience-related features had the strongest predictive power.
* Proper preprocessing significantly improved model performance.
* Feature selection reduced redundancy and improved model interpretability.

---

## Project Structure

```text
├── notebook_55.ipynb      # Main notebook
├── results_55.csv         # Model predictions/results
├── ML_pro.pdf             # Full project report
├── README.md
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Author

**Ahmad Abu-Ras**

Machine Learning & Data Science Enthusiast

Tel Aviv University Graduate




