#  Retail Revenue Forecasting Project

This project is implementation of time series forecasting using SARIMA. It was built by **Bagus Permono** as part of a learning journey in data science.

## Project Objective
To predict future monthly revenue for a retail business based on historical data using the SARIMA model. This project simulates real-world forecasting needs for budgeting and planning.

## Dataset
The dataset used is a dummy retail revenue dataset consisting of:
- Month (Date)
- Revenue
- Marketing Spend
- Holiday Flag

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn
- statsmodels (SARIMAX)
- scikit-learn (evaluation metrics)

## Key Steps
1. Load and prepare time series data
2. Visualize trends and seasonality
3. Split data into training and testing
4. Build and fit a SARIMA model
5. Forecast revenue for the test set
6. Evaluate performance using MAE and RMSE
7. Forecast next 6 months of revenue

## Results
The model was able to reasonably predict future revenue and visualize the trends. This lays a foundation for more advanced forecasting work in finance and business analytics.

## Author
**Bagus Permono**  
📧 baguspermono1@gmail.com  
🔗 [GitHub](https://github.com/baguspermono)

## To Run This Project
```bash
pip install -r requirements.txt
jupyter notebook retail_revenue_forecast_bagus.ipynb
```
