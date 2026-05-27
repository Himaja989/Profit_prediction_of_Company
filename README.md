# Profit Prediction of a Company Using Machine Learning

This project predicts company profit based on business spending patterns using machine learning models. The goal is to help understand how factors such as R&D Spend, Administration Spend, and Marketing Spend influence company profitability.

## Project Overview

Businesses need to make smart decisions about where to invest their money. This project uses the `50_Startups.csv` dataset to analyze company spending and predict profit using different regression models.

The project includes data exploration, visualization, preprocessing, model building, model comparison, and business interpretation.

## Dataset

Dataset used: `50_Startups.csv`

The dataset contains 50 records and 5 columns:

- R&D Spend
- Administration
- Marketing Spend
- State
- Profit

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regression

## Project Workflow

1. Imported and explored the dataset
2. Checked for missing values and duplicate records
3. Performed statistical analysis
4. Created visualizations such as heatmaps, pairplots, and boxplots
5. Checked correlation between features
6. Performed feature selection and preprocessing
7. Split the data into training and testing sets
8. Built multiple regression models
9. Evaluated models using R² Score, RMSE, and MAE
10. Compared model performance and identified the best model

## Model Performance

| Model | R² Score | RMSE | MAE |
|---|---|---|---|
| Linear Regression | 0.9001 | 8995.91 | 6979.15 |
| Ridge Regression | 0.8960 | 9178.35 | 7396.36 |
| Lasso Regression | 0.9001 | 8995.90 | 6979.15 |
| Random Forest Regression | 0.9049 | 8777.18 | 6357.49 |

## Best Model

Random Forest Regression performed the best among all models with the highest R² score and lowest error values.

## Key Insights

- R&D Spend and Marketing Spend are the most important factors for predicting profit.
- Administration Spend has a smaller impact compared to other spending categories.
- Random Forest gives better prediction accuracy, while Linear Regression is easier to interpret.
- Machine learning can help businesses make better resource allocation decisions.

## Limitations

- The dataset is small, with only 50 records.
- Only a few spending-related features are included.
- External business factors such as market trends, competition, and economic conditions are not included.
- The model may not generalize well to all companies without more data.

## Conclusion

This project shows how machine learning can be used to predict company profit based on spending behavior. By comparing multiple regression models, Random Forest Regression was found to be the most accurate model for this dataset.

## How to Run the Project

### 1. Clone the Repository

git clone https://github.com/your-username/your-repository-name.git

Navigate to the Project Folder
cd Profit_Prediction_of_Company

3. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn

5. Open Jupyter Notebook
jupyter notebook

7. Run the Notebook
Profit_Prediction_Of_Company.ipynb
Files in This Repository
Profit_Prediction_Of_Company.ipynb
50_Startups.csv
Profit_Prediction_Presentation_Content.txt
README.md

Author
Himaja Arabati
