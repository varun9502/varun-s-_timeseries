German Electricity Demand Forecasting
Overview

This project compares benchmark, statistical, machine-learning and deep-learning methods for German electricity-demand forecasting. It also evaluates how forecast accuracy changes when models are refreshed annually, semiannually or quarterly.

Models
Mean, Naive, Drift and Seasonal Naive
SARIMA and SARIMAX
AdaBoost regression
Hourly LSTM
Installation

Run in Google Colab or Jupyter with Python 3.

pip install pandas numpy matplotlib scipy statsmodels scikit-learn tensorflow joblib requests holidays
How to Run
Open the notebook.
Keep internet access enabled for electricity and weather-data retrieval.
Run every cell from top to bottom.
Allow the SARIMA search and LSTM training to finish.
Review the final forecast tables, refresh-policy comparison and saved plots.
Main Outputs

The workflow produces:

Data-quality checks
EDA and stationarity analysis
Benchmark forecasts
SARIMA and SARIMAX results
AdaBoost and LSTM forecasts
Model-refresh comparisons
Accuracy, runtime and maintenance evaluation
Main Finding

Annual Seasonal Naive provides the strongest operational update policy, while semiannual AdaBoost offers a useful balance between prediction accuracy and model-maintenance effort.
