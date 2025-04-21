# Stock Price Prediction using AI Models (MSFT & FB)
This repository presents a comprehensive research and implementation project focused on predicting stock prices of Microsoft (MSFT) and Facebook (FB) using machine learning (ML) and deep learning (DL) techniques. The study employs models including Random Forest, XGBoost, and Long Short-Term Memory (LSTM) networks, supported by detailed preprocessing, feature engineering, and comparative evaluation.
## Project Structure
•	Sohail(stock_market).ipynb: Jupyter Notebook containing data preprocessing, feature engineering, model development, and visualization for stock price forecasting.

•	Sohail Anjum (FPR)docx: Full research project report including literature review, methodology, ethical considerations, results discussion, and references.
## Objective
The aim of this project is to forecast the daily closing stock prices of MSFT and FB using historical market data and financial indicators, leveraging machine learning algorithms to compare predictive performance.
## Models Used
•	Random Forest – High accuracy, best generalization performance (R²: 0.9198).

•	LSTM (Long Short-Term Memory) – Time-series focused model, underperformed in this multi-stock dataset (R²: 0.2047).

•	XGBoost – Achieved extremely high training accuracy (R²: 0.99998) but overfitted the data.
## Methodology Overview
### 1.Data Collection:
o	Financial data and stock prices from Yahoo Finance, Nasdaq, and SEC EDGAR.
o	Dataset contains 140+ S&P 500 companies (2010–2016).
### 2.Preprocessing & Feature Engineering:
o	Missing value handling, normalization, technical indicators (RSI, MACD, Bollinger Bands, etc.).
### 3.Model Training:
o	Hyperparameter tuning via Grid Search.
o	Evaluation using MAE, MSE, RMSE, and R².
### 4.Visualization:
o	Predicted vs Actual price plots.
o	Comparative performance graph of all three models.
## Key Results
### Model     	MAE	MSE	RMSE	R² Score

Random Forest	  0.0482	0.00638	0.0799	0.9198

LSTM	          0.2256	0.0633	0.2517	0.2047

XGBoost	        0.0875	0.0198	0.1406	0.99998
## Ethical Considerations
•	All data sources are public and ethically sourced.
•	No personal or sensitive data used.
•	The project is for academic use only—no financial decisions are based on this research.
## Future Work
•	Include sentiment analysis and macroeconomic variables.
•	Test advanced models such as GRU or Transformer.
•	Explore ensemble methods for better generalization.


