# Car Price Prediction Project

## Overview
This project is about predicting car prices using data and machine learning. It uses information like the car model, fuel type, transmission, and manufacturing year. Inflation adjustments are included to improve price predictions for future years.

## Goals
- Predict car prices accurately.
- Adjust prices for inflation.
- Compare the results of different models.

## Dataset
The data includes:
- **Car Name**: The model of the car (e.g., "Toyota Corolla GLI").
- **Year Of Upload**: The year the data was recorded.
- **Model Year**: The year the car was made.
- **SE/LE**: Indicates a variant (e.g., "YES" or "NO").
- **Fuel Type**: Type of fuel (e.g., "Petrol").
- **Car Price**: The price of the car in lakhs.
- **Transmission**: Transmission type (e.g., "Manual").

## Steps
1. **Clean the Data**:
   - Rename columns to a consistent format.
   - Convert "SE/LE" to numbers (1 for "YES," 0 for "NO").

2. **Adjust for Inflation**:
   - Update old car prices using estimated inflation rates.

3. **Prepare Features**:
   - Turn text data (e.g., car name) into numbers.
   - Standardize numerical data (e.g., model year).

## Models Used
### Gradient Boosting
- A machine learning model that combines small decision trees for better predictions.

### Neural Network
- A model with layers that process data step-by-step.

## Results
- The models predict car prices with an average error of around 4 lakhs.

## Example Prediction
Input:
  - Car Name: Toyota Corolla GLI
  - Model Year: 2013
  - Fuel Type: Petrol
  - Transmission: Manual
  - SE/LE: 1

Output:
  - Predicted Price: 25.00 Lakhs

## Requirements
- Python 3.8+
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `tensorflow`

## Next Steps
- Add features like mileage and car condition.
- Use better inflation data.
- Try combining models for more accurate predictions.

## Summary
This project predicts car prices using data and machine learning. By adjusting for inflation, it provides more realistic price estimates for the future.

