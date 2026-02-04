# Natural Gas Prices vs. Tesla Stock Performance

This project analyzes the relationship between global natural gas prices and Tesla’s stock performance using time-series data and machine learning models.

## Overview
- Collected and combined external datasets for natural gas prices and Tesla stock (price & volume)
- Cleaned, normalized, and resampled daily data into monthly aggregates
- Explored correlations using Pearson correlation with significance testing
- Built predictive models to forecast Tesla price and volume

## Models Used
- Linear Regression
- K-Nearest Neighbors (KNN)
- Random Forest

## Evaluation Metrics
- R²
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Random Forest achieved the strongest predictive performance among tested models.

## Tools
Python, pandas, scikit-learn, statsmodels, matplotlib
