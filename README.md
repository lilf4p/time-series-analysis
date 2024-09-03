# Time Series Analysis
A basic time series analysis of the temperature data in the appliances [dataset](https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction#).
The dataset contains values from 9 sensors placed in 9 room of the house. 
Temperatures have been measured for 4.5 months, from 2016-01-11 to 2016-05-27 with 10 minutes interval. It's useful to plot the 9 time series for a first look to data. From the initial plot it's clear data have a lot of noise, so before plotting the auto-correlogram we try to reduce it. Also plots show a positive trend as temperature values are increasing in time. 
Using trend remotion technique and DFT we can plot the auto-correlogram and study the time series auto-correlation, which reveal interesting daily patterns.
