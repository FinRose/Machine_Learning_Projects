# Predicting Airline Financial Losses During Aviation Disruptions

## Project Overview
This project builds a machine learning model to predict airline daily financial losses during disruption events using operational indicators such as cancelled flights, rerouted flights, additional fuel costs, and passengers impacted.

## Objective
To develop a regression model that predicts airline daily financial losses and identify the operational factors contributing most to those losses.

## Dataset
Global Civil Aviation Disruption Dataset.

Features include:
- airline
- country
- cancelled_flights
- rerouted_flights
- additional_fuel_cost_usd
- passengers_impacted

Target Variable:
- estimated_daily_loss_usd

## Model Used
Decision Tree Regressor

## Model Performance
R² Score: 0.856  
RMSE: 131,475

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Key Insights
- Passenger impact strongly correlates with financial losses
- Flight cancellations significantly increase operational costs
- Rerouted flights increase fuel expenditure
