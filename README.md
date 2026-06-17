<div align="center">

#  Job Acceptance Prediction using Machine Learning

<p>
A complete Machine Learning pipeline for predicting candidate job acceptance using data preprocessing, feature engineering, feature selection, and supervised classification models.
</p>

<p>
<img src="https://img.shields.io/badge/Python-3.11-blue?logo=python">
<img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas">
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter">
<img src="https://img.shields.io/badge/Status-Completed-success">
</p>

</div>

---

## 📌 Project Overview

This project aims to predict whether a candidate will be accepted for a job position based on demographic, educational, professional, and technical background information.

The project follows a complete machine learning workflow, from raw data exploration to model evaluation and comparison.

### Key Components

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data Cleaning & Preprocessing
* ⚙️ Feature Engineering
* 🔍 Missing Value Handling
* 📈 Outlier Detection
* 🎯 Feature Selection
* 🤖 Model Training
* 📉 Performance Evaluation
* 🏆 Model Comparison

---

## 📂 Dataset

The dataset contains candidate-related information such as:

| Feature Category        | Examples                                    |
| ----------------------- | ------------------------------------------- |
| Professional Background | Years of Experience, Previous Salary        |
| Education               | Degree Level                                |
| Technical Skills        | Programming Languages & Technology Stack    |
| Demographics            | Country, Age Group                          |
| Employment History      | Previous Work Experience                    |
| Additional Features     | Development Background and Other Attributes |

### Target Variable

```text
Accepted = 1
Not Accepted = 0
```

---

## ⚙️ Data Preprocessing

### Missing Value Handling

Different strategies were applied depending on the feature type:

* Statistical Imputation
* Distribution-Based Sampling
* Domain-Driven Imputation
* Category Grouping

### Outlier Detection

Outliers were detected and handled using the **Interquartile Range (IQR)** method.

### Feature Engineering

* One-Hot Encoding
* Country → Continent Mapping
* Technology Stack Categorization
* Categorical Encoding

### Feature Selection

Mutual Information (MI) was used to identify the most informative features and reduce dimensionality.

---

## 🤖 Machine Learning Models

The following supervised learning models were implemented and evaluated:

| Model                     | Purpose                 |
| ------------------------- | ----------------------- |
| Random Forest             | Ensemble Learning       |
| AdaBoost                  | Boosting                |
| Logistic Regression       | Linear Classification   |
| K-Nearest Neighbors (KNN) | Instance-Based Learning |

Hyperparameter tuning was performed to improve generalization performance and reduce overfitting.

---

## 📊 Evaluation Metrics

Model performance was assessed using:

* ROC Curve
* AUC Score
* Cross Validation
* Confusion Matrix
* Accuracy
* Precision

---

## 🏆 Results

### Best Performing Model

✅ **Random Forest Classifier**

The Random Forest model achieved the highest validation performance and demonstrated strong generalization ability.

### Main Findings

* Technical skills significantly influence hiring decisions.
* Experience-related features are highly predictive.
* Proper preprocessing substantially improves model performance.
* Feature selection reduces redundancy and improves interpretability.

---

## 📁 Project Structure

```bash
job-acceptance-prediction-ml/
│
├── notebook_55.ipynb      # Main project notebook
├── results_55.csv         # Prediction results
├── ML_pro.pdf             # Full project report
├── README.md
│
└── figures/               # Optional visualizations
```

---

## 🛠 Technologies Used

<p>
<img src="https://skillicons.dev/icons?i=python">
<img src="https://skillicons.dev/icons?i=github">
<img src="https://skillicons.dev/icons?i=vscode">
</p>

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📄 Project Report

A detailed project report describing the methodology, preprocessing pipeline, model selection, and evaluation can be found in:

```text
ML_pro.pdf
```

---

## 👨‍💻 Author

### Ahmad Abu-Ras

Machine Learning & Data Science Enthusiast

🎓 Tel Aviv University Graduate

🔗 GitHub: https://github.com/Ahmadaburas22

---

<div align="center">

⭐ If you found this project interesting, feel free to star the repository.

</div>
