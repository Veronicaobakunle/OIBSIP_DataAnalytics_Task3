# OIBSIP_DataAnalytics_Task3
# OIBSIP - Task 3

## Description
This project predicts house sale prices using the Ames Housing dataset. It covers data exploration, feature preparation, and building regression models to estimate SalePrice based on property characteristics.

## Files
- Veronica_Obakunle__task_3.ipynb - Jupyter notebook with full analysis
- train.csv - Housing dataset (1460 rows, 81 features)

## Key Steps
- Explored and prepared housing features for modeling
- Trained and compared three regression models: Linear Regression, Ridge, and Lasso
- Evaluated models using MSE, RMSE, and R2 score
- Visualized top positive and negative feature coefficients driving price predictions

## Results
| Model | RMSE | R2 |
|---|---|---|
| Linear Regression | 34,643.93 | 0.8435 |
| Ridge (alpha=1.0) | 34,608.62 | 0.8438 |
| Lasso (alpha=1000) | 37,523.89 | 0.8164 |

Ridge regression performed best, slightly outperforming plain Linear Regression while regularizing the coefficients.

## Tools Used
- Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Author
Veronica Obakunle
