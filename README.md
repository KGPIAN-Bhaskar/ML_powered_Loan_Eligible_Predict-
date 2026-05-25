# ML-Powered Loan Eligibility Prediction System

## Project Overview

This project is an end-to-end Machine Learning application designed to predict whether an applicant is eligible for a loan based on customer information and financial attributes. The model analyzes applicant details and predicts loan approval status, helping financial institutions make faster and more data-driven decisions.

The system uses data preprocessing, feature engineering, machine learning algorithms, and performance evaluation techniques to generate accurate predictions.

---

## Problem Statement

Banks and financial institutions receive thousands of loan applications. Manual verification is time-consuming and may lead to inconsistent decisions.

The objective of this project is to build a machine learning model that can:

- Predict loan eligibility
- Reduce manual effort
- Improve decision-making
- Minimize lending risk

---

## Features

✔ Data preprocessing and cleaning  
✔ Handling missing values  
✔ Feature engineering  
✔ Exploratory Data Analysis (EDA)  
✔ Categorical variable encoding  
✔ Model training and testing  
✔ Loan eligibility prediction  
✔ Model performance evaluation  
✔ Feature importance visualization  

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier
- XGBoost (optional)

### Tools
- Jupyter Notebook
- GitHub

---

## Dataset Features

The model uses customer-related features such as:

- Gender
- Marital Status
- Dependents
- Education
- Self Employed
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

Target Variable:

Loan_Status

- Y → Eligible
- N → Not Eligible

---

## Machine Learning Workflow

### Step 1: Data Collection
Load loan dataset.

### Step 2: Data Cleaning
- Handle missing values
- Remove inconsistencies

### Step 3: Exploratory Data Analysis
- Distribution analysis
- Correlation analysis
- Data visualization

### Step 4: Feature Engineering
- Encoding categorical variables
- Scaling numerical features

### Step 5: Model Building
Train multiple models:

1. Logistic Regression
2. Random Forest
3. Decision Tree

### Step 6: Model Evaluation

Evaluation metrics:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Results

Model performance:

| Model | Accuracy |
|---------|----------|
| Linear Regression | 66% |
| Random Forest | 79% |

Random Forest achieved the highest accuracy.

---

## Project Structure

```bash
Loan_Eligibility_Prediction/
│
├── Loan_datasets_pred.xlsx
├──loan_code.ipynb
├── README.md

```

## Installation

Clone repository:

```bash
git clone https://github.com/your-username/Loan_Eligibility_Prediction.git
```

Move to project directory:

```bash
cd Loan_Eligibility_Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run application:

```bash
python app.py
```

---

## Future Improvements

- Deploy using Streamlit
- Add Explainable AI (SHAP)
- Add real-time loan prediction API
- Hyperparameter tuning
- Improve prediction accuracy

---

## Conclusion

This project demonstrates how machine learning can support financial institutions by automating loan approval decisions and reducing credit risk.

---

## Author

Bhaskar Mandal

GitHub:
https://github.com/KGPIAN-Bhaskar

LinkedIn:
https://www.linkedin.com/in/bhaskar-mandal/
