# Household Electric Power Consumption Forecasting Using LSTM

## Project Overview
This project predicts household electricity consumption using historical electricity measurements from the Household Electric Power Consumption dataset.

## Dataset
- Source: Kaggle / UCI Machine Learning Repository
- Data frequency: Minute-level measurements
- Selected records: 10,000 consecutive records
- Target variable: Global Active Power

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Google Colab

## Methodology
1. Load the electricity consumption dataset.
2. Handle missing values.
3. Normalize numerical data.
4. Generate sequences from the previous 60 minutes.
5. Build and train an LSTM model.
6. Evaluate predictions using MAE and RMSE.
7. Visualize actual versus predicted electricity consumption.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Expected Outcome
The model forecasts the next minute's household electricity consumption based on historical measurements.

## How to Run
Open the project notebook in Google Colab and execute the code cells in order.

## Author
Student Project
