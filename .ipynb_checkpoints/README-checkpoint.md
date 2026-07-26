# Employee Turnover Prediction using Logistic Regression

A Machine Learning project that predicts whether an employee is likely to leave the organization using **Logistic Regression**. This project demonstrates binary classification, model evaluation, and the use of **L1 (Lasso)** and **L2 (Ridge)** regularization to improve model generalization. Logistic regression is a common baseline algorithm for employee attrition prediction tasks. :contentReference[oaicite:0]{index=0}

---

## Project Overview

Employee turnover (or attrition) is an important HR analytics problem. Predicting employee turnover helps organizations identify employees who may leave and supports data-driven retention strategies.

This project includes:
- Data loading and preprocessing
- Train-test split
- Logistic Regression model
- Model evaluation
- Overfitting check using training and testing accuracy
- L1 (Lasso) Regularization
- L2 (Ridge) Regularization
- Classification Report
- Accuracy comparison

---

## Dataset

The dataset contains **1,350 employee records** with **16 features**.

### Features

- Job_Satisfaction
- Performance_Rating
- Years_At_Company
- Work_Life_Balance
- Distance_From_Home
- Monthly_Income
- Education_Level
- Age
- Num_Companies_Worked
- Employee_Role
- Annual_Bonus
- Training_Hours
- Department
- Annual_Bonus_Squared
- Annual_Bonus_Training_Hours_Interaction

**Target Variable**

- Employee_Turnover
  - `0` → Employee Stays
  - `1` → Employee Leaves

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
employee_turnover_logisticReg/
│
├── employee_turnover_project.ipynb
├── employee_turnover.csv
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Ashwakkattubadi/employee_turnover_logisticReg.git
```

Move into the project directory:

```bash
cd employee_turnover_logisticReg
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Model Workflow

1. Load Dataset
2. Split Features and Target
3. Train-Test Split
4. Train Logistic Regression
5. Check Training vs Testing Accuracy
6. Apply L1 (Lasso) Regularization
7. Apply L2 (Ridge) Regularization
8. Evaluate Model Performance

---

## Model Evaluation

The notebook evaluates the model using:

- Accuracy Score
- Classification Report
- Training Accuracy
- Testing Accuracy

The comparison between training and testing accuracy helps determine whether the model is:
- Well fitted
- Overfitting
- Underfitting

---

## Regularization

### L1 Regularization (Lasso)

- Performs feature selection
- Shrinks less important feature coefficients to zero
- Helps reduce overfitting

### L2 Regularization (Ridge)

- Shrinks feature coefficients
- Reduces model complexity
- Improves generalization

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- ROC-AUC Curve
- Confusion Matrix Visualization
- Feature Importance Analysis
- Compare with Decision Tree, Random Forest, and XGBoost

---

## Author

**Ashwak Kattubadi**

GitHub: https://github.com/Ashwakkattubadi

---
