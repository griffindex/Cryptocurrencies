# Cryptocurrencies

## Overview
The purpose of this repository is to apply an unsupervised machine learning model to a cryptocurrency dataset. The cryptocurrency dataset is sourced as a .csv file from https://min-api.cryptocompare.com. A clustering algorithm is used to find what cryptocurrencies are on the trading market and how they could be grouped to create a classification system

## Summary
The Elbow Curve method is used to determine that 4 is the best value to use for the K means algorithm.
![Elbow Curve hvPlot](/Resources/df_elbowcurve.png)
An interactive 3d scatter plot is created to visualize the tradeable cryptocurrencies. There are 532 tradable cryptocurrencies. A 2d scatter plot visualizes these cryptocurrencies where TotalCoinsMined is x and TotalCoinSupply is y.
![2d Scatter Plot](/Resources/2d_scatter.png)