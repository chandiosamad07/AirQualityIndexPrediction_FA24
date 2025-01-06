# AirQualityIndexPrediction_FA24
This repository contains data science projects along with their corresponding datasets. It includes data preprocessing, analysis, visualizations, and predictive modeling using various machine learning techniques. Each project is well-documented with code, explanations, and results.

<h1></h1>
<h1><center>Air Quality Index Prediction </center></h1>

## Introduction

Air pollution has a significant impact on the environment. Monitoring and predicting the Air Quality Index (AQI) helps us assess the quality of air and take precautionary measures to minimize exposure to pollutants.


---
### **Features**:
- **PM2.5**: Particulate matter.
- **PM10**: Particulate matter.
- **NO2**: Nitrogen Dioxide.
- **CO**: Carbon Monoxide.
- **SO2**: Sulfur Dioxide.
- **O3**: Ozone.

---

# **Problem Statement**
Information on air quality is frequently very unclear, which makes it challenging for peoples to respond to pollution flows. Data on air quality is accessible, but it typically absences the specifics required to identify patterns as take preventative action. That is the issue what we seek to resolve by our project. By developing a model that forecasts the quality of the air in Karachi. The system's precise daily projections can aid people, and the officials in better understanding pollution patterns and implementing effective responses.

# **Business Questions**


1. How does air quality vary over time?
2. Is there specific months when air  pollution levels are consistently higher?
3. Is there specific season when pollution levels are consistently higher?
4. Which pollutants have the most significant impact on AQI (e.g., PM2.5, PM10, CO, NO2)?
5. What are the primary sources of the key air pollutants?
6. Can the model accurately predict future AQI levels to help authorities and individuals prepare for poor air quality days?
7. How many days per year are categorized as "unhealthy" or worse according to AQI standards?
8. What steps can individuals take to minimize exposure during periods of poor air quality?



# **Dataset**
Ahmedabad India data set downloaded from Kaggle was used for training while for testing Karachi data set was scrapped out of many datasets and combined.

# **Insights**  (Based on Analysis)

1. How does air quality vary over time (daily, monthly, or annually)?

Insight: Air quality exhibits daily and monthly fluctuations. Specific pollutants like PM2.5 and PM10 show spikes during certain months, likely related to seasonal activities such as winter heating or increased industrial output.

Example Time series plots for pollutants (e.g., PM2.5, PM10, NO2) show noticeable trends over time.

2. Is there specific months when pollution levels are consistently higher?

Insight: Pollution levels are consistently higher during winter months (e.g., December and January). This may be due to lower temperatures trapping pollutants closer to the ground (thermal inversion) and increased use of heating.

Example: Peaks in PM2.5 and PM10 levels during these months in time series plots.

3. Is there specific season when pollution levels are consistently higher?

Insight: Winter appears to be the most polluted season, likely due to atmospheric conditions and human activities.

Example: Seasonal patterns in PM2.5 and PM10 plots.

4. Which pollutants have the most significant impact on AQI (e.g., PM2.5, PM10, CO, NO2)?

Insight: PM2.5, PM10, and NO2 show the strongest correlation with AQI, indicating that these are the primary contributors.

Example: Correlation heatmap highlights strong relationships between these pollutants and AQI.

5. What are the primary sources of the key pollutants?

Insight:
PM2.5 and PM10: Likely from vehicular emissions, industrial activities, and construction.
NO2: Likely from traffic and industrial combustion.
CO: Likely from incomplete combustion in vehicles.

Example: Trends and correlations suggest the sources based on common pollutant origins.

6. Can the model accurately predict future AQI levels to help authorities and individuals prepare for poor air quality days?

Insight: Prediction capability depends on the model's performance and dataset quality. Time series analysis provides the foundation for building predictive models using algorithms like ARIMA, LSTM, etc.

Example: Observed temporal trends in pollutant levels.

7. How many days per year are categorized as "unhealthy" or worse according to AQI standards?

Insight: A high proportion of days fall into the "Unhealthy" category based on AQI bucket distribution.

Example AQI bucket countplot provides a breakdown of days by category.

8. What steps can individuals take to minimize exposure during periods of poor air quality?

Insight:
Limit outdoor activities during high AQI periods.
Use air purifiers and masks.

Example: Periods of high PM2.5 and PM10 levels suggest times to avoid outdoor exposure.

## **Future Work**

The dataset does not contain geographical segmentation, but additional data can be integrated to answer this question.
