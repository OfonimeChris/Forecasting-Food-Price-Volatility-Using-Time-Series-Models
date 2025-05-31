# Forecasting-Food-Price-Volatility-Using-Time-Series-Models
## Table of Content
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Libraries Used](#Libraries-used)
- [Data Sources](#data-sources)
- [Data Column](#data-column)
- [Project Structure](#project structure)
- [How to Use](#how to Use)
- [Results](#results)
- [Future Work](#future work)
- [Acknowledgments](#acknowledgments)
  
## Project Overview
This project focuses on analyzing and forecasting food price volatility using various time series models. The analysis is conducted using Python and leverages several statistical and machine learning libraries to process, explore, and model food price data.
## Key Features
•	Data Preparation & Exploration: Loads and cleans food price data, performs initial exploration, and prepares the dataset for analysis.
•	Trend & Seasonality Analysis: Visualizes price trends and decomposes time series data to identify underlying patterns.
•	Time Series Modeling: Utilizes ARIMA and Exponential Smoothing models to forecast food price volatility.
•	Performance Evaluation: Assesses model accuracy using metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).
## Libraries Used
•	Pandas: Data manipulation and analysis.
•	NumPy: Numerical computations.
•	Matplotlib & Seaborn: Data visualization.
•	Statsmodels: Statistical modeling, including seasonal decomposition and ARIMA.
•	Scikit-learn: Model evaluation metrics.
## Dataset
The dataset (foodprice_data.csv) contains monthly food price data for various products from January 2017 to February 2025. Each row represents a food product, and columns contain price values for each month.
## Data Columns
•	Products: Names of the food products.
•	Monthly Prices: Columns labeled by date (e.g., 2017-01-01, 2017-02-01, etc.) containing price values.
## Project Structure
1.	Data Preparation & Exploration:
o	Load and inspect the dataset.
o	Clean and transform the data for analysis.
o	Handle missing values and ensure data integrity.
2.	Trend & Seasonality Analysis:
o	Visualize price trends over time.
o	Decompose time series data to observe trends, seasonality, and residuals.
o	Perform stationarity tests (e.g., Augmented Dickey-Fuller test).
3.	Time Series Modeling:
o	Fit ARIMA models to forecast food prices.
o	Apply Exponential Smoothing techniques.
o	Compare model performance using evaluation metrics.
4.	Results & Insights:
o	Summarize findings from the analysis.
o	Highlight key trends and volatility patterns.
o	Provide actionable insights based on model forecasts.
## How to Use
1.	Prerequisites:
o	Python 3.x
o	Libraries listed in the import section of the notebook.
2.	Setup:
o	Clone the repository or download the notebook.
o	Install required libraries using pip install -r requirements.txt.
3.	Execution:
o	Run the Jupyter notebook (Forecasting Food Price Volatility Using Time Series Models.ipynb) step-by-step to reproduce the analysis.
## Results
The project demonstrates the application of time series models to forecast food price volatility. Key outputs include:
•	Visualizations of price trends and seasonal patterns.
•	Model performance metrics (MSE, MAE).
•	Forecasted price values for future periods.
## Future Work
•	Incorporate external factors (e.g., inflation, weather data) to improve model accuracy.
•	Experiment with advanced machine learning models (e.g., LSTM, Prophet).
•	Expand the dataset to include more products or regions for broader insights.
## Acknowledgments
•	The dataset used in this project is sourced from Statistics Canada. (Year). Table 18-10-0245-02: Monthly average retail prices for selected food products. Retrieved from https://www150.statcan.gc.ca/
•	Special thanks to the open-source community for providing the libraries and tools used in this analysis.
