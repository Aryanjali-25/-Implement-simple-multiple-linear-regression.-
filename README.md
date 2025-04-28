# -Implement-simple-multiple-linear-regression.-
# Weather Analysis Project

This project performs a comprehensive analysis of Seattle weather data using linear regression to understand temperature patterns.

## Analysis Process

1. Import and Preprocess the Dataset
   - Load the weather data from CSV
   - Handle missing values
   - Convert date to datetime format
   - Select relevant features (precipitation, minimum temperature, wind)

2. Split Data into Train-Test Sets
   - Split data into 80% training and 20% testing sets
   - Use random_state=42 for reproducibility
   - Features: precipitation, minimum temperature, wind
   - Target: maximum temperature

3. Fit Linear Regression Model
   - Use sklearn.linear_model.LinearRegression
   - Train model on training data
   - Make predictions on test data

4. Model Evaluation
   - Calculate Mean Absolute Error (MAE)
   - Calculate Mean Squared Error (MSE)
   - Calculate R-squared (R²) score
   - Interpret model performance metrics

5. Visualization and Interpretation
   - Plot regression line (actual vs predicted temperatures)
   - Interpret coefficients for each feature:
     - Rain impact on temperature
     - Minimum temperature effect
     - Wind effect
     - Base temperature

## Requirements

- pandas
- numpy
- matplotlib
- scikit-learn

## Data Description

The dataset includes:
- Precipitation (mm)
- Minimum temperature (°C)
- Maximum temperature (°C)
- Wind speed (m/s)
