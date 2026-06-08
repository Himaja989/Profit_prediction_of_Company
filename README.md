# Profit Prediction of a Company Using Machine Learning

## Overview

Profit prediction is an important business analytics problem that helps organizations understand how investment decisions influence overall profitability. This project uses machine learning techniques to predict company profit based on spending across different business functions.

Using the 50 Startups dataset, the project analyzes the impact of Research and Development (R&D) Spend, Administration Spend, Marketing Spend, and State on company profit. Multiple regression models are implemented and compared to identify the most accurate approach for profit forecasting.

## Business Problem

Companies allocate resources across research, operations, and marketing activities with the goal of maximizing profitability. Understanding which investments contribute most to business growth can support better strategic planning and budgeting decisions.

This project aims to answer the following questions:

* How does R&D spending affect profit?
* What impact does marketing expenditure have on profitability?
* Which business expenses contribute most to company profit?
* Can machine learning accurately predict future profit?

## Dataset

Dataset: 50_Startups.csv

The dataset contains information from 50 startup companies.

| Feature         | Description                              |
| --------------- | ---------------------------------------- |
| R&D Spend       | Amount spent on research and development |
| Administration  | Administrative expenses                  |
| Marketing Spend | Marketing and advertising expenses       |
| State           | Company location                         |
| Profit          | Company's profit (Target Variable)       |

### Dataset Statistics

* Total Records: 50
* Input Features: 4
* Target Variable: Profit

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Development Environment

* Jupyter Notebook

## Project Workflow

### Data Exploration

* Imported and analyzed the dataset
* Reviewed dataset structure and feature information
* Generated descriptive statistics

### Data Cleaning

* Checked for missing values
* Checked for duplicate records
* Validated data quality

### Exploratory Data Analysis

* Correlation analysis
* Distribution analysis
* Feature relationship analysis
* Outlier detection

### Data Visualization

* Correlation heatmap
* Pair plots
* Box plots
* Feature distribution plots

### Data Preprocessing

* Encoded categorical variables
* Selected relevant features
* Prepared data for modeling

### Model Development

* Split dataset into training and testing sets
* Trained multiple regression models
* Evaluated model performance

### Model Comparison

* Compared model accuracy using evaluation metrics
* Identified the best-performing model

## Machine Learning Models

### Linear Regression

A baseline regression model used to understand linear relationships between spending patterns and profit.

### Ridge Regression

A regularized regression model that reduces overfitting by applying L2 regularization.

### Lasso Regression

A regression model that applies L1 regularization and can perform feature selection.

### Random Forest Regression

An ensemble learning model that combines multiple decision trees to improve prediction accuracy and robustness.

## Evaluation Metrics

The models were evaluated using the following metrics:

### R² Score

Measures how well the model explains the variation in profit.

### Root Mean Squared Error (RMSE)

Measures the average magnitude of prediction errors.

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

## Model Performance

| Model                    | R² Score | RMSE    | MAE     |
| ------------------------ | -------- | ------- | ------- |
| Linear Regression        | 0.9001   | 8995.91 | 6979.15 |
| Ridge Regression         | 0.8960   | 9178.35 | 7396.36 |
| Lasso Regression         | 0.9001   | 8995.90 | 6979.15 |
| Random Forest Regression | 0.9049   | 8777.18 | 6357.49 |

## Best Performing Model

Random Forest Regression achieved the highest predictive performance.

Results:

* R² Score: 0.9049
* RMSE: 8777.18
* MAE: 6357.49

The model provided the most accurate profit predictions and outperformed the other regression techniques used in this project.

## Key Findings

* R&D Spend is the strongest predictor of company profit.
* Marketing Spend also contributes significantly to profitability.
* Administration Spend has a comparatively smaller impact on profit.
* Machine learning can assist organizations in making data-driven investment decisions.
* Random Forest Regression provides the highest prediction accuracy, while Linear Regression offers better interpretability.

## Limitations

* The dataset contains only 50 records.
* Limited business variables are available.
* External factors such as market conditions, competition, customer behavior, and economic trends are not included.
* Results may not generalize to all industries without additional data.

## Future Improvements

Potential enhancements include:

* Hyperparameter tuning
* Gradient Boosting Regression
* XGBoost implementation
* Larger and more diverse datasets
* Interactive business dashboards
* Deployment as a web application using Flask or FastAPI
* Cloud deployment using AWS or Azure

## Project Structure

```text
Profit_Prediction_of_Company/
│
├── Profit_Prediction_Of_Company.ipynb
├── 50_Startups.csv
├── Profit_Prediction_Presentation_Content.txt
└── README.md
```

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Himaja989/profit-prediction-company.git
```

### Navigate to the Project Directory

```bash
cd profit-prediction-company
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open the Notebook

```bash
Profit_Prediction_Of_Company.ipynb
```

## Skills Demonstrated

* Data Analysis
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Feature Engineering
* Machine Learning
* Regression Modeling
* Model Evaluation
* Business Analytics
* Python Programming

## Conclusion

This project demonstrates how machine learning can be used to predict company profit based on business spending patterns. By analyzing historical investment data and comparing multiple regression models, Random Forest Regression was identified as the most accurate model for profit prediction.

The results highlight the importance of R&D and Marketing investments in driving profitability and demonstrate how predictive analytics can support strategic business decision-making.

## Author

Himaja Arabati

Master of Science in Computer Science


