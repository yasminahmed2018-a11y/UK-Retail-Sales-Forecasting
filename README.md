UK Retail Sales Forecasting
Project Overview
This project analyses monthly UK retail sales volume from January 2021 to September 2026 and uses time-series forecasting to estimate the next six months.

The project focuses on the retail sector as a whole. It does not analyse an individual company, shop, or product.
Data Source
- Publisher: UK Office for National Statistics (ONS)
- Dataset: Retail Sales
- Selected series: RSI: Volume Seasonally Adjusted: All Retailers ex fuel: All Business Index (J467)
- Measure: Index, base year = 100
- Period analysed: January 2021 – September 2026
ONS Retail Sales dataset
Project Steps
1. Data understanding and selection of the relevant ONS series.
2. Data cleaning and preparation using Python.
3. Exploratory data analysis and visualisation.
4. Time-series forecasting using the Holt-Winters Exponential Smoothing method.
5. Model evaluation using a 12-month test period.
Forecasting Results
The model was evaluated using the final 12 months as a test set:
- MAE: 0.88 index points
- RMSE: 1.08 index points
The project also generates a six-month forecast. Forecast values are estimates, not guaranteed outcomes.
Files
- UK_Retail_Sales_Analysis.ipynb – complete analysis and forecasting notebook.
- UK_Retail_Sales_Cleaned.csv – cleaned monthly dataset.
- UK_Retail_Sales_Forecast.csv – six-month forecast results.
- Retail_Sales_Forecasting_Report.md – written project report.
Tools
Python, Pandas, NumPy, Matplotlib, and Statsmodels.
Important Note
The analysis uses a national, seasonally adjusted retail volume index excluding fuel. It should not be interpreted as the sales performance of a specific company or product.
