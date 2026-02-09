# linear-regression-lab-assignment-by-aditi-pandey-and-ruqqiya-noor
This repository contains a comprehensive Linear Regression lab assignment using a COVID-19 dataset with 30 records. It includes EDA, Simple and Multiple Linear Regression, Polynomial Regression, Ridge and Lasso Regularization, model evaluation using MSE, RMSE and R², and residual analysis implemented in Python without seaborn.


📌 Objective

The objective of this assignment is to implement, analyze, and compare various Linear Regression models, including:

Simple Linear Regression

Multiple Linear Regression

Polynomial Regression

Ridge Regression

Lasso Regression

using a real-world inspired COVID-19 dataset.

🧠 Problem Statement

Given a dataset with multiple input features and a continuous target variable, perform end-to-end analysis using different linear regression techniques and evaluate model performance using appropriate metrics.

📁 Dataset Description

1.Dataset Name: COVID-19 Dataset (Synthetic)

2.Number of Records: 30

#Features:

1.Day

2.Tests_Conducted

3.Active_Cases

4.Recovered

5.Deaths

6.Target Variable: Confirmed_Cases (Continuous)

7.The dataset is clean, contains no missing values, and is suitable for regression analysis.

🛠️ Tools & Technologies Used

1.Python

2.Jupyter Notebook / Google Colab

3.Libraries:

4.Pandas

5.NumPy

6.Matplotlib

7.Scikit-Learn

⚠️ Note: Seaborn is not used in this assignment.

🔍 Methodology
1️⃣ Exploratory Data Analysis (EDA)

1.Loaded and inspected the dataset

2.Computed summary statistics

3.Checked for missing values and outliers

4.Visualized feature distributions

5.Created correlation heatmap using Matplotlib

2️⃣ Simple Linear Regression

1.Used Tests_Conducted as the independent variable

2.Built and evaluated the model

3.Plotted regression line

4.Interpreted slope and intercept

3️⃣ Multiple Linear Regression

1.Used multiple input features

2.Analyzed feature coefficients

3.Evaluated performance using MSE, RMSE, and R² score

4️⃣ Polynomial Regression

1.Applied polynomial transformation to capture non-linear relationships

2.Compared performance with linear regression

5️⃣ Regularization Techniques

1.Implemented Ridge Regression to reduce overfitting

2.Implemented Lasso Regression for feature selection

3.Compared coefficients and model performance

6️⃣ Model Diagnostics

1.Plotted residuals vs predicted values

2.Validated regression assumptions

📈 Evaluation Metrics

1.Mean Squared Error (MSE)

2.Root Mean Squared Error (RMSE)

3.R² Score

✅ Results & Observations

1.Multiple Linear Regression performed better than Simple Linear Regression

2.Polynomial Regression captured non-linear patterns

3.Ridge Regression improved model stability

Lasso Regression helped in identifying important features
