# Restaurant Sales ML Pipeline

This project demonstrates an **end-to-end machine learning workflow** to predict restaurant order totals using Python and scikit-learn.

## Project Overview

- Load and clean raw restaurant sales data
- Perform feature engineering (e.g., extracting date components)
- Handle missing values, encode categorical features, and scale numerical features
- Split data into training and testing sets
- Train and evaluate multiple regression models:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
- Compare model performance using MSE, RMSE, MAE, and R²
- Save the best performing model and preprocessing objects for future use

## Best Model

- **Random Forest Regressor** performed the best with:
  - R² ≈ 0.998
  - Very low RMSE and MAE
 
## How to Run
1. Clone this repository:
```bash
git clone https://github.com/AymanBerri/restaurant-sales-ml.git
```
2. Open the notebook in Google Colab or Jupyter.
3. Follow the notebook step by step — it’s fully documented with explanations and visualizations.

## Skills & Tools
- Python, Pandas, NumPy
- Scikit-learn (Regression, Preprocessing, Imputation, Scaling)
- Matplotlib, Seaborn (visualizations)
- End-to-end ML pipeline development

## Notes
The target variable `(order_total)` can technically be calculated from price × quantity, but this project demonstrates a complete ML pipeline for learning purposes.
