# Air Pollution in India – Data Analysis

## Introduction
Air pollution poses one of the most critical environmental and health challenges in India. This project aims to analyze air quality data across different Indian cities to uncover patterns, compare pollutant levels, and visualize trends over time. 

The goal is to derive meaningful insights into which pollutants contribute most to poor air quality, which regions are affected the most, and how air quality changes seasonally or annually.

## Dataset
Used the dataset [AirQuality in India - Data Analysis](https://www.kaggle.com/code/harimo/airquality-in-india-data-analysis) from Kaggle.

## Libraries Used
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Exploratory Data Analysis (EDA) Insights
The EDA explores temporal, spatial, and pollutant-wise variations in India’s air quality.
- **Pollution Trends by City**
  - Major metropolitan cities like Delhi, Kolkata, and Mumbai show significantly higher PM2.5 and PM10 levels.
  - Smaller cities show moderate air quality but with occasional spikes during specific seasons (especially winter).
- **Temporal Trends**
  - There is a seasonal pattern in pollution:
    - Winter months (Nov–Jan) show peak PM2.5 and PM10 concentrations.
    - Monsoon months (Jul–Sep) show the cleanest air due to rainfall reducing dust and particulate matter.
- Correlation Between Pollutants
  - High positive correlation between PM2.5, PM10, and NOx, suggesting vehicular and industrial emissions as major sources.
  - Ozone (O3) shows a weaker correlation, often peaking in summer months due to photochemical reactions.
- AQI Category Distribution
  - Majority of readings fall in Moderate and Poor categories.
  - Some regions (especially Northern India) frequently cross into Very Poor or Severe AQI zones.
- City-Wise AQI Comparison
  - Delhi records the worst AQI averages, followed by Lucknow, Kolkata, and Kanpur.
  - Southern cities like Chennai and Bengaluru have relatively better air quality.
- Pollutant Impact
  - PM2.5 and PM10 are dominant pollutants affecting AQI in most cities.
  - NO2 and CO levels also indicate strong links to vehicular exhaust.

## Conclusion
- Air pollution in India is a serious and recurring issue, particularly during winter months.
- Northern and industrial regions suffer from persistent particulate pollution (PM2.5/PM10).
- Vehicle emissions and crop-burning appear as major sources in polluted cities.
- Continuous monitoring and policy interventions are essential for sustainable air quality improvement.