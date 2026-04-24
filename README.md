# Edutech Solution – Data Science Internship

## Task 4: Linear Regression

## Project Overview

This project is part of the **Edutech Solution Data Science Internship – Task 4**, focused on implementing **Linear Regression** using the House Price Dataset.

The objective of this task is to build a machine learning model that predicts house prices based on input features and evaluates model performance using **RMSE (Root Mean Squared Error)**.

---

## Objective

* Understand the fundamentals of regression modeling
* Split the dataset into training and testing sets
* Train a Linear Regression model
* Predict values for the test dataset
* Evaluate model performance using RMSE

---

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* GitHub

---

## Dataset
  ### Dataset Name:
  **HousePrice Dataset**

### Files Used:

* `house_prices.csv`
* `predictions.csv`
* `notebooks.ipynb`

The dataset contains house-related features used to predict the target variable: **House Price**.

---

## Project Workflow

### 1. Data Loading

Imported the dataset using Pandas and checked the structure of the data.

### 2. Data Preprocessing

* Checked for missing values
* Selected useful numerical features
* Prepared input (`X`) and target (`y`) variables

### 3. Train-Test Split

Used `train_test_split()` from Scikit-learn to divide the dataset into training and testing sets.

### 4. Model Training

Applied **Linear Regression** using Scikit-learn:

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X_train, y_train)
```

### 5. Prediction

Generated predicted values for the test dataset.

### 6. Model Evaluation

Evaluated model performance using:

```python
from sklearn.metrics import mean_squared_error
import numpy as np

rmse = np.sqrt(mean_squared_error(y_test, y_pred))
print(rmse)
```

---

## Final Outcome

* Successfully trained a Linear Regression model
* Generated predicted values report
* Evaluated model accuracy using RMSE
* Learned the fundamentals of regression modeling

---

## Interview Questions

### What is Regression?

Regression is a supervised machine learning technique used to predict continuous numerical values such as house prices, salary prediction, temperature forecasting, etc.

### What is RMSE and why is it used?

RMSE stands for **Root Mean Squared Error**.

It is used to measure how far the predicted values are from the actual values. A lower RMSE value indicates better model performance.

---

## Repository Structure

```text
Task-4-Linear-Regression/
│
├── house_prices.csv
├── predictions.csv
├── notebooks.ipynb
├── Task4_Documentation.pdf
├── README.md
`

## Task 4: Outcome 
<img width="1919" height="1015" alt="Outcome_Task4 1" src="https://github.com/user-attachments/assets/43c3d690-f069-45cf-bee2-c5bdfd022503" />

<img width="1919" height="1021" alt="Outcome_Task4 2" src="https://github.com/user-attachments/assets/79eb73d2-c3b9-4ee8-b2b1-4a2c6677a87b" />

---
This project helps in understanding the core concept of regression and prepares the foundation for advanced machine learning models.
