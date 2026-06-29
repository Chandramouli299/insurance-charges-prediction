# insurance-charges-prediction
# Insurance Charges Prediction Using Machine Learning

## Project Overview

This project predicts individual medical insurance charges using machine learning regression techniques. The model analyzes demographic and health-related information to estimate insurance costs accurately.

## Problem Statement

Medical insurance charges are influenced by several factors such as age, BMI, smoking habits, and region. This project builds regression models to predict insurance charges based on these features.

## Dataset Features

### Input Features

* Age
* Sex
* BMI
* Children
* Smoker
* Region

### Target Variable

* Insurance Charges

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Data Visualization
5. Train-Test Split
6. Multicollinearity Check (VIF)
7. Data Preprocessing
8. Model Training
9. Model Evaluation
10. Model Comparison

## Machine Learning Models Used

* Linear Regression
* Ridge Regression
* Lasso Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## Data Preprocessing

* Duplicate Removal
* One-Hot Encoding
* Feature Scaling
* ColumnTransformer
* Pipeline Implementation

## Key Insights

* Smoking status is one of the strongest factors affecting insurance charges.
* Age and BMI also have a significant impact on medical costs.
* Model comparison helps identify the best-performing regression algorithm.

## Project Structure

```text
Insurance-Charges-Prediction/
│
├── insurance.ipynb
├── insurance.csv
├── README.md
```

## Future Improvements

* Deploy the model using Streamlit.
* Perform hyperparameter tuning using Optuna.
* Build an interactive insurance charge prediction web application.

## Author

**Chandramouli Neerukonda**

* GitHub: https://github.com/Chandramouli299
* LinkedIn: https://www.linkedin.com/in/chandramouli-neerukonda-69204a268/
