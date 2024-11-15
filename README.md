# Bank Loan Sanction Amount Prediction (Regression)

This project focuses on predicting loan sanction amounts for bank customers based on various features like age, income, credit score, property type, and more. By comparing different regression models, the project identifies the most accurate model for this prediction task.

> **Note**: This project was completed in 2021, and the results are based on data and models available at that time. Predictions and model accuracy may vary if the project is rerun with updated data or model improvements available in recent years.

**Project Documentation**: For detailed information about this project, kindly refer to the [Project_Overview](https://github.com/SHETTY-DHIRAJ/Bank-Loan-Sanction-Amount-Prediction/blob/main/Dependent%20Resources/Project_Overview.pdf) document.

## Project Overview

- **Objective**: Predict the loan sanction amount for a customer using multiple features available in a dataset provided by the bank.
- **Machine Learning Models Used**: Linear Regression, Decision Tree Regression, Support Vector Regression (SVR), Random Forest Regression, Bayesian Regression.
- **Techniques**: Exploratory Data Analysis (EDA) for data visualization, data cleaning, feature engineering, and regression modeling.

## Screenshots

### Research Related Screenshots

<p align="center">
  <img src="https://github.com/SHETTY-DHIRAJ/Bank-Loan-Sanction-Amount-Prediction/blob/main/Dependent%20Resources/Heatmap%20to%20find%20null%20value.jpg" alt="Heatmap to find null value" width="600">
</p>
<p align="center"><em>Heatmap to find null value</em></p>

<p align="center">----</p>

<p align="center">
  <img src="https://github.com/SHETTY-DHIRAJ/Bank-Loan-Sanction-Amount-Prediction/blob/main/Dependent%20Resources/Boxplot%20of%20Age%20and%20Income%20Stability.jpg" alt="Boxplot of Age and Income Stability" width="600">
</p>
<p align="center"><em>Boxplot of Age and Income Stability</em></p>

<p align="center">----</p>

<p align="center">
  <img src="https://github.com/SHETTY-DHIRAJ/Bank-Loan-Sanction-Amount-Prediction/blob/main/Dependent%20Resources/Jointplot%20of%20Loan%20Amount%20Request%20(USD)%20and%20Current%20Loan%20Expenses%20(USD).jpg" alt="Jointplot of Loan Amount Request (USD) and Current Loan Expenses (USD)" width="600">
</p>
<p align="center"><em>Jointplot of Loan Amount Request (USD) and Current Loan Expenses (USD)</em></p>

<p align="center">----</p>

<p align="center">
  <img src="https://github.com/SHETTY-DHIRAJ/Bank-Loan-Sanction-Amount-Prediction/blob/main/Dependent%20Resources/Boxplot%20of%20Profession%20and%20Age.jpg" alt="Boxplot of Profession and Age" width="600">
</p>
<p align="center"><em>Boxplot of Profession and Age</em></p>

## Problem Statement

Given a dataset with various customer parameters, the goal is to:
- Predict the loan amount sanctioned by the bank based on customer-provided data.
- Conduct EDA to visualize relationships between variables and identify significant attributes.
- Evaluate and compare multiple regression models based on R² scores to determine the best-performing model.

## Features

1. **Data Cleaning and Preprocessing**
   - Fill missing values based on logical assumptions or statistical measures.
   - Apply One-Hot Encoding and Label Encoding for categorical variables.

2. **Exploratory Data Analysis (EDA)**
   - Visualize the data using plots like heatmaps, boxplots, barplots, and joint plots.
   - Analyze correlations between attributes such as income stability, age, property location, profession, and credit score.
   - Created multiple visualizations to understand the impact of each features.

3. **Key Plots and Insights**
   - Heatmaps to identify missing values and correlations.
   - Boxplots, bar plots, and joint plots to examine relationships between features.

4. **Machine Learning Models Training**
   - Training multiple regression models to predict loan sanction amounts.
   - Models used: Linear Regression, Decision Tree Regression, SVR, Random Forest Regression, and Bayesian Regression.

5. **Model Evaluation**
   - Assess model performance using metrics such as R² score, Mean Absolute Error (MAE), and Root Mean Square Error (RMSE).
   - Selecting the model with the highest R² score for accurate loan prediction.

## Project Structure

- **Notebooks**: Jupyter notebook containing overall research code, located in the `research.ipynb` file.
  
- **Data**: 
  - `classified-data.csv`: Contains the dataset used for analysis and prediction.

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook for running code interactively
- Libraries: pandas, matplotlib, seaborn, scikit-learn, numpy

## Workflow

1. **Data Collection and Preprocessing:**

   - Removed irrelevant columns.
   - Imputed missing values using mean values and custom functions based on related attributes (e.g., filling missing income stability based on age).
   - Used encoding for categorical variables such as gender, income stability, profession, and property location.

3. **Exploratory Data Analysis:**
    
   - Heatmap: Identified missing values and correlations among features.
   - Boxplots: Analyzed the relationship between income stability, property location, and dependents.
   - Bar Plots: Examined the distribution of loan amount requests across different locations and professions.
   - Joint Plot: Explored the relationship between current loan expenses and loan amount request.
   - Distplot: Displayed the distribution of customer ages.

4. **Model Training & Model Evaluation:**

   - Train regression models on 80% of the data, leaving 20% for testing.
   - Measure the R² score, MAE, and RMSE for each model.
   - Select the model with the best performance for predicting loan amounts.

## Results

   - The project concluded with a comparison of all models, with insights into the most effective algorithms for this regression task.
   - Random Forest yielded the highest R2 scores, making them suitable choices for this dataset.

## Acknowledgements
Resources and references for this project include:

   - [GeeksforGeeks](https://www.geeksforgeeks.org/)
   - [Stack Overflow](https://stackoverflow.com/)
   - [Seaborn Documentation](https://seaborn.pydata.org/)
   - [Scikit-learn Documentation](https://scikit-learn.org/stable/)
