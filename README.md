# Delhi Weather & Air Quality Insights Dashboard and Report – 2025

### Climate Analytics | Environmental Data Analysis | Python | Statistical Modeling

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Data-Pandas-150458?logo=pandas)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-F7931E?logo=scikitlearn)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview

The **Delhi Weather & Air Quality Insights Dashboard and Report – 2025** is a data analytics project focused on examining the relationship between weather conditions and air pollution patterns in Delhi.

The project analyzes historical meteorological and air quality measurements, including temperature, humidity, atmospheric pressure, wind speed, AQI, PM2.5, PM10, CO, and NO2.

Using Python-based data analytics, statistical techniques, anomaly detection, and regression modeling, the project identifies seasonal climate variations, extreme weather conditions, pollution trends, and potential environmental risks.

The primary objective is to transform raw environmental data into meaningful insights through analytical modeling and data visualization.

## Problem Statement

Delhi experiences significant seasonal variations in weather conditions and air pollution levels. Understanding the relationship between meteorological factors and pollutant concentrations is important for identifying environmental patterns and potential climate risks.

This project addresses the challenge through systematic data preprocessing, exploratory analysis, statistical modeling, and visualization.

## Project Objectives

- Analyze monthly and seasonal temperature variations.
- Identify extreme heatwave and coldwave conditions.
- Examine AQI fluctuations and seasonal pollution patterns.
- Detect unusual weather conditions using statistical anomaly detection.
- Investigate relationships between meteorological variables and air pollutants.
- Analyze the influence of wind speed on PM2.5 concentrations.
- Develop a composite Climate Risk Score to identify high-risk environmental periods.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python 3.x |
| Development Environment | Google Colab, Jupyter Notebook |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistical Analysis | SciPy |
| Modeling | Linear Regression |
| Version Control | Git, GitHub |

## Key Features & Implementation

### 1. Data Preprocessing and Feature Engineering
- Imported and processed environmental datasets using Pandas.
- Standardized column names and converted date columns into datetime format.
- Handled missing values and organized observations chronologically.
- Generated analytical features such as month, heat intensity, cold intensity, Z-score, and risk score.

### 2. Exploratory Data Analysis (EDA)
- Analyzed monthly average, minimum, and maximum temperatures.
- Examined seasonal temperature variations.
- Investigated monthly AQI distributions and pollution fluctuations.
- Studied relationships between weather parameters and pollutant concentrations.

### 3. Heatwave and Coldwave Analysis
- Defined heatwave conditions using temperatures above 40°C.
- Identified coldwave conditions using temperatures below 7°C.
- Calculated heat and cold intensity indicators.
- Analyzed extreme temperature periods and seasonal severity.

### 4. Statistical Anomaly Detection
- Implemented Z-score-based anomaly detection using SciPy.
- Identified unusual temperature observations.
- Examined deviations from normal environmental patterns.

### 5. Correlation and Regression Analysis
- Applied Pearson correlation to investigate relationships between environmental variables.
- Studied temperature and AQI relationships.
- Examined humidity and pollution patterns.
- Investigated the relationship between wind speed and PM2.5 dispersion.
- Applied Linear Regression using Scikit-learn to study temperature as an independent variable and AQI as a dependent variable.

### 6. Climate Risk Score Model
Developed a custom composite scoring approach incorporating:
- Temperature extremes.
- AQI levels.
- Wind speed factors.

The model provides an analytical indicator for identifying periods associated with elevated environmental risk.

## Data Visualizations

The project includes multiple analytical visualizations:

- Seasonal Temperature Trend Line Plot
- Heatwave Intensity Timeline
- Coldwave Intensity Timeline
- Monthly AQI Heatmap
- Weather and Pollution Correlation Matrix
- Temperature vs. AQI Regression Plot
- Wind Speed vs. PM2.5 Scatter Plot
- Temperature Volatility Bar Chart
- Z-Score Anomaly Detection Scatter Plot
- Climate Risk Score Timeline

## Key Insights

The analysis highlighted several environmental patterns:

- Maximum heatwave intensity was observed during peak summer months.
- AQI levels showed worsening patterns under low wind speed conditions.
- A positive correlation was identified between temperature and AQI in the analyzed dataset.
- Winter months exhibited higher PM2.5 concentrations.
- Statistical anomalies were identified during seasonal transitions.
- Climate Risk Scores increased during periods of extreme environmental conditions.

*These observations represent analytical findings from the dataset and should not be interpreted as proof of causation.*

## Project Structure

```text
Delhi-Weather-Air-quality-Insights-Dashboard-and-Report---2025/
│
├── Delhi_Weather_&_Air_quality_Insights_Report_2025.ipynb
│
├── LICENSE
│
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x
- Google Colab or Jupyter Notebook
- Basic knowledge of Python and data analytics

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/Shivaniyadav628/Delhi-Weather-Air-quality-Insights-Dashboard-and-Report---2025.git
```

**2. Navigate to the project directory**

```bash
cd Delhi-Weather-Air-quality-Insights-Dashboard-and-Report---2025
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

**4. Open the Jupyter Notebook**

```bash
jupyter notebook
```

**5. Run the notebook**

Open:

`Delhi_Weather_&_Air_quality_Insights_Report_2025.ipynb`

Execute the cells sequentially.

**Dataset:** Ensure the input environmental dataset is available at the file path configured in the notebook. The repository currently contains the notebook and README; the dataset should be supplied separately if it is not included.

## Future Enhancements

- Implement time-series forecasting using ARIMA or Prophet.
- Develop a machine learning model for AQI prediction.
- Build an interactive dashboard using Streamlit or Plotly.
- Deploy the analytics application to a cloud platform.
- Extend the analysis to multiple Indian cities.
- Incorporate real-time weather and air quality data.

## Applications

- Environmental data analysis and monitoring.
- Urban climate risk assessment.
- Air pollution trend analysis.
- Weather pattern research.
- Data-driven environmental decision support.

## Author

**Shivani Yadav**

B.Tech Computer Science and Engineering

GitHub: [Shivaniyadav628](https://github.com/Shivaniyadav628)

Project: [Delhi Weather & Air Quality Insights – 2025](https://github.com/Shivaniyadav628/Delhi-Weather-Air-quality-Insights-Dashboard-and-Report---2025)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**If you find this project useful, consider giving the repository a star!**
