# MINOR_PROJECT_01

#  Diabetes Prediction Using Logistic Regression

##  Project Overview

This project predicts whether a patient is likely to have diabetes based on medical attributes using a Supervised Machine Learning algorithm (Logistic Regression).

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

---

##  Objective

The objective of this project is to build a predictive model that can classify whether a patient has diabetes based on health-related features.

---

##  Dataset

**Dataset Name:** Pima Indians Diabetes Dataset

**Source:** https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable**

- Outcome
  - 0 → No Diabetes
  - 1 → Diabetes

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

##  Project Structure

```
Diabetes-Prediction/
│
├── data/
│   └── diabetes.csv
│
├── notebook/
│   └── Diabetes_Prediction.ipynb
│
├── model/
│   └── logistic_regression.pkl
│
├── results/
│   ├── histogram.png
│   ├── outcome_distribution.png
│   └── confusion_matrix.png
│
├── report/
│   └── Project_Report.pdf
│
├── requirements.txt
│
└── README.md
```

---

##  Data Preprocessing

The following preprocessing steps were performed:

- Dataset loading
- Missing value checking
- Duplicate value checking
- Feature selection
- Feature scaling using StandardScaler
- Train-Test Split (80:20)

---

##  Exploratory Data Analysis (EDA)

EDA includes:

- Statistical Summary
- Histogram of Features
- Outcome Distribution
- Correlation Analysis

---

##  Machine Learning Model

Algorithm Used:

- Logistic Regression

---

##  Model Evaluation

The model was evaluated using the following Classification Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

##  Results

The Logistic Regression model achieved good classification performance in predicting diabetes.

Example Results:

| Metric | Value |
|---------|---------|
| Accuracy | 81% |
| Precision | 78% |
| Recall | 74% |
| F1 Score | 76% |

*(Results may vary depending on the train-test split.)*

---

##  How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Diabetes-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Diabetes_Prediction.ipynb
```

Run all cells.

---

##  Libraries Used

```python
pandas
numpy
matplotlib
scikit-learn
```

---

##  Future Improvements

- Hyperparameter Tuning
- Random Forest Classifier
- XGBoost Classifier
- Deployment using Flask/Streamlit
- Interactive Web Application

---

##  Author

**Ravi Kishan**

B.Tech CSE(AIML) Student

---

##  License

This project is created for educational purposes.
