# Ice Cream Revenue Prediction

Predicts daily ice cream shop revenue from temperature using Linear Regression (scikit-learn).

## Dataset
500 records, 2 columns: `Temperature` (°C) and `Revenue`. No missing values.
Source: YBI Foundation public dataset (loaded directly from GitHub in the notebook).

## Approach
1. Explore the data (summary stats, missing values, correlation, scatter plot)
2. 70/30 train-test split
3. Train a Linear Regression model
4. Evaluate with MAE, MAPE, MSE and R²
5. Visualize the fitted line and actual vs predicted values
6. Predict revenue for new temperatures

## Results
- Correlation between temperature and revenue: about 0.99
- R² about 0.98, MAE about 19 (about 4% error) on the test set
- Each 1°C increase adds about 21.5 to revenue

## How to run
Open `Icecream_Revenue_Prediction.ipynb` in Google Colab and click Runtime > Run all.

## Tech
Python, pandas, matplotlib, scikit-learn
