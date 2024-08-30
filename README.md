# ISSSD-2024
Here you will find the datasets and code necessary to reproduce the work titled *Comparative Study on Predicting Dose Equivalent Rate Using Advanced Machine Learning Techniques and Time Series Models*.

To test with additional datasets, use the following link to download data: https://radnet.epa.gov/radnet-public/query.do. The provided codes are intended for use with a single column (Clean Dataset). Ensure to filter the datasets to remove missing or low-quality data.

The Datasets folder includes data from four different cities. The "Clean" dataset refers to the San Antonio dataset that has undergone a quality check, which removes missing data and eliminates the first two columns (dates).

The Scatter Plots folder displays the results for the test dataset from the five different models.

The Comparison Measured vs Forecasted folder contains the test data for each model, where column 1 of each CSV file represents the measured data and column 2 represents the forecasted data.

Two scripts are provided: one for Colab and one in .py format.
