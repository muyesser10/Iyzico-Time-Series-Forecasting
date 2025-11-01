🧾 Iyzico Transaction Volume Forecasting 

This project aims to forecast the total daily transaction volume for the last three months of 2020 for Iyzico, a financial technology company that provides payment infrastructure for e-commerce businesses and individual users.

📊 Project Objective

To help Iyzico predict future transaction volumes per merchant, enabling better financial planning and resource management.

⚙️ Steps Implemented

Data Exploration (EDA):
Examined date ranges, total transactions, and total payment amounts.

Feature Engineering:
Created new features including date-based, lag, rolling mean, and exponentially weighted mean (EWM) variables.

Modeling:
Built a LightGBM model and evaluated performance using the SMAPE (Symmetric Mean Absolute Percentage Error) metric.

Validation:
Used data before October 2020 for training and the last 3 months of 2020 for validation.

🧠 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

LightGBM

📈 Results

The model successfully captured the time-series patterns of each merchant and produced forecasts evaluated with SMAPE.
Feature importance plots were also generated to interpret the most influential variables.
