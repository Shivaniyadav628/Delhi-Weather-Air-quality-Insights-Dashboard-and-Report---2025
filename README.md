 CLIMATE & AIR QUALITY ANALYTICS PROJECT – DELHI 2025
 
 PROJECT OVERVIEW

This project presents a comprehensive climate and air quality analysis using historical weather and pollution data for Delhi (2025).

The primary objective is to extract meaningful insights related to:

Seasonal temperature patterns

Heatwave and coldwave intensity

Pollution behavior and AQI fluctuations

Climate risk evaluation

The project demonstrates real-world applications of:

Data preprocessing

Statistical analysis

Anomaly detection

Regression modeling

Composite risk scoring

 OBJECTIVES

Analyze seasonal temperature trends

Identify heatwave intensity (> 40°C)

Identify coldwave intensity (< 7°C)

Detect extreme anomalies using Z-Score

Study correlation between weather & pollution

Evaluate wind impact on PM2.5 levels

Develop a Climate Risk Score model

Build a professional visualization dashboard

 TOOLS & TECHNOLOGIES USED


Google Colab (Cloud-based Jupyter Notebook Environment)

 Programming Language

Python 3.x

 PYTHON LIBRARIES USED

pandas - Data cleaning & manipulation

numpy - Numerical computations

matplotlib - Data visualization

seaborn -	Statistical plotting & heatmaps

scikit-learn - Linear regression modeling

scipy	Z-score - anomaly detection

 DATA PREPROCESSING
 
Data Cleaning Steps

Imported dataset using pandas

Standardized column names

Converted date_ist to datetime format

Sorted dataset chronologically

Handled missing values

Generated descriptive statistics

Feature Engineering

Created new analytical features:

month

heat_intensity

cold_intensity

z_score

risk_score

 EXPLORATORY DATA ANALYSIS (EDA)
 
1️.  Monthly Temperature Trend

Calculated mean, minimum, and maximum temperatures

Identified seasonal peaks

Visualized temperature variation over time

2️.  Heatwave Analysis

Threshold defined as temperature > 40°C

Measured excess temperature intensity

Identified extreme heat days

3️. Coldwave Analysis

Threshold defined as temperature < 7°C

Calculated cold stress index

Analyzed winter severity

4️. AQI Trend Analysis

Monthly AQI heatmap

Seasonal pollution distribution

Peak pollution months identification

5️. Correlation Analysis

Pearson correlation matrix

Temperature vs AQI relationship

Humidity vs Pollution impact

Wind speed vs PM2.5 dispersion effect

 ADVANCED ANALYTICS PERFORMED
 
 Heat Intensity Calculation

 Cold Intensity Calculation

 Z-Score Anomaly Detection
 
from scipy import stats

 Regression Modeling

Model Type: Linear Regression

Independent Variable → Temperature

Dependent Variable → AQI Index

from sklearn.linear_model import LinearRegression
 Climate Risk Score Model

Custom composite score developed using:

Temperature extremes

AQI index

Wind speed factor

This score identifies high-risk environmental periods.

 VISUALIZATIONS INCLUDED

Seasonal Temperature Line Plot

Heatwave Intensity Timeline

Coldwave Timeline

AQI Monthly Heatmap

Correlation Matrix Heatmap

Regression Plot (Temperature vs AQI)

Wind Speed vs PM2.5 Scatter Plot

Temperature Volatility Bar Chart

Anomaly Detection Scatter Plot

Climate Risk Score Timeline

All visualizations were created using:

matplotlib

seaborn

 KEY INSIGHTS DERIVED

Maximum heatwave intensity observed during peak summer months.

AQI levels worsen during low wind speed conditions.

Strong positive correlation identified between temperature and AQI.

Winter months show significantly higher PM2.5 concentration.

Temperature anomalies detected during seasonal transitions.

Climate Risk Score peaks during extreme weather events.

 PROJECT STRUCTURE
Climate-Analytics-Project

data.csv
 -> Climate_Analytics_Colab.ipynb
 -> README.md
->  report.pdf
 BUSINESS & POLICY RELEVANCE

Supports climate risk monitoring systems

Assists environmental policy formulation

Useful for urban heat island mitigation strategies

Helps in pollution forecasting and intervention planning

FUTURE ENHANCEMENTS

Time Series Forecasting (ARIMA / Prophet)

Machine Learning AQI Prediction Model

Interactive Dashboard using Plotly

Deployment using Streamlit

Multi-city comparative climate analysis

 PROJECT LEVEL

 Advanced Academic Project
 Portfolio-Level Data Science Project
 Industry-Standard Visualization
 Policy-Oriented Analytical Framework

 AUTHOR

Shivani Yadav

Data Analytics & Climate Intelligence Project

2026
