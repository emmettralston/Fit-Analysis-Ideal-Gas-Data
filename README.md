# Temperature vs Pressure Analysis

## Project Overview

This project analyzes the relationship between temperature and pressure using linear least squares fitting and linear chi-squared fitting methods. The analysis includes data reading, model fitting, and visualization of results with error bars and fit lines.


## Project Description

The goal of this project is to fit temperature vs. pressure data using two different linear fitting methods:
1. **Linear Least Squares Fit**: A simple linear fit of the data.
2. **Linear Chi-Squared Fit**: A weighted linear fit that accounts for uncertainties in the data.

The project involves calculating fit parameters, y-intercepts, and chi-squared values, and visualizing the results with error bars and fit lines.

## Data

The dataset used is located in the `SampleData.csv` file. The relevant columns are:
- **Temperature**: Temperature values for fitting.
- **Pressure**: Pressure values corresponding to the temperatures.
- **Pressure Uncertainty**: Uncertainty in pressure measurements.
- **Temperature Error**: Uncertainty in temperature measurements.

## Fitting Methods

### Linear Least Squares
- **Description**: Performs a linear fit using ordinary least squares.
- **Calculations**: Computes the slope and intercept of the fit line.
- **Y-Intercept Temperature**: Determines the temperature at which the fit line crosses the y-axis.

### Linear Chi-Squared Fit
- **Description:** Computes a weighted linear fit considering uncertainties.
- **Calculations:** Determines fit parameters, chi-squared value, and y-intercept temperature.

## Visualization

- **Error Bars**: Representing uncertainties in temperature and pressure measurements.
- **Fit Lines**: Both chi-squared and linear fits.
- **Y-Intercept Lines**: Vertical lines indicating y-intercept temperatures for both fitting methods.

## Requirements

- **Python 3.x**
- **pandas**: For data manipulation
- **numpy**: For numerical operations
- **matplotlib**: For plotting
