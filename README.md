📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of air quality data collected from multiple monitoring stations across India.

📊 Analyzed 108,000+ records from 110 stations (2015–2020)
🎯 Goal: Understand pollution patterns and factors influencing Air Quality Index (AQI)
🔍 Identified trends, distributions, and anomalies in pollutant levels
📁 Dataset Information

The dataset includes:

🏭 Pollutants:
PM2.5, PM10
NO, NO2, NOx
CO, SO2, O3
Benzene, Toluene

📅 Features:
Date
Station ID
AQI values
AQI Categories

⚙️ Tech Stack
🐍 Python
📊 Pandas, NumPy
📈 Matplotlib, Seaborn
📉 SciPy

🧹 Data Cleaning & Preprocessing
Removed Xylene column due to high missing values (~78%)
Applied station-wise median imputation for better accuracy
Handled remaining missing values using global median
Extracted time-based features:
Year
Month
Quarter

🔍 Exploratory Data Analysis
Analyzed pollutant distributions using statistical methods
Studied AQI distribution and category trends
Identified:
Skewness
Outliers
Variability in pollutant levels

📊 Visualizations
📌 Histograms & Density plots
📌 Box plots for outlier detection
📌 AQI category distribution charts
📌 Multi-variable comparison plots
💡 Key Insights
Many pollutants show high skewness, indicating extreme pollution events
AQI is mostly concentrated in Moderate to Poor categories
Pollution levels vary significantly across time and stations
