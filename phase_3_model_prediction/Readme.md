Phase 3: Air Quality Prediction Model (35 Points)
Objective: Develop predictive models to forecast pollutant concentrations (specifically CO, NOx, or Benzene) using the features derived from the time-series data.

Model Requirements:
Choose ONE from each category:

Basic Models (Required):
Linear Regression with time-based features
Random Forest
XGBoost
Advanced Models (Optional - 5 Bonus Points):
ARIMA or SARIMA
LSTM (Note: This requires more computational resources)
Feature Engineering Requirements:

Develop time-based features (hour, day, month)
Create lagged features from previous time periods
Generate rolling statistics (averages, standard deviations)
Document your feature engineering approach
Evaluation Process:

Use a chronological train/test split appropriate for time series data
Evaluate using MAE and RMSE metrics
Compare your model to a baseline (previous value prediction)
Integration with Kafka:

Develop a mechanism to use your trained model with incoming Kafka messages
Document how your system would operate in a real-time environment
