The **primary goal** of this project is to develop a robust regression model to predict used car prices for a reseller 
based on various listed features and specifications. 
In addition to predicting prices, the project focuses on identifying feature importance and mitigating overfitting 
through the application of regularisation techniques.



**Problem Statement**
Price Prediction: Model car prices based on features like mileage, fuel type, and performance.
Market Analysis: Explore trends and preferences in the used car market, by type, region, or other metrics.
Feature Importance: Identify the most important factors influencing car prices (e.g., fuel type, mileage, age).


**Dataset**
The dataset for this task has been scraped from a German online car trading company, AutoScout. 
The AutoScout data is a comprehensive collection of information on various used vehicles, capturing a wide array of attributes.
	• The dataset is a CSV file containing 15915 records across 23 columns.
	• The columns contain information on attributes such as engine specifications, vehicle weight, power, 
  number of previous owners, vehicle condition and so on.
There are also columns describing safety, comfort, and entertainment specifications in a bundled way. 
These columns contain all the extra features present as a string and might need some preprocessing.


**Tasks Overview**
The data pipeline for this task involves the following steps:

Dataset Overview
Data Preprocessing
Data Visualisation & Exploration
Model Building
Regularisation
