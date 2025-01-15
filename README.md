# LSTM-Project

## Overview
This project uses an LSTM neural network to forecast future values in a time series. The model is trained on normalized historical data and evaluated using the R² score. Predictions for the next 15 time steps are visualized for analysis.

## Features
- LSTM-based sequential model for forecasting.
- Data preprocessing with MinMaxScaler.
- Evaluation using R² score.
- Visualization of actual vs. predicted values.

## Usage
1. **Preprocess the Data**: Load the dataset, normalize it, and prepare it for training.
2. **Train the Model**: Use the LSTM model to train on the time series data.
3. **Evaluate Performance**: Calculate the R² score to assess accuracy.
4. **Forecast Future Values**: Predict the next 15 time steps and visualize results.

Run the script or notebook to execute the steps above.

## Results
- The model achieved an **R² score of 0.9933** in above example, indicating high accuracy in predictions.
- Visualizations clearly show how well the model tracks actual values and forecasts future trends.

## Visualizations
1. **Actual vs Predicted Values**: Comparison of the true values and the model's predictions during the training period.
2. **Forecast for the Next 15 Time Steps**: Visualizing the model's ability to predict unseen data points.
