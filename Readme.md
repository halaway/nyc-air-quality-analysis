# About The Project 

While still a work in progress, this work hopes to capture the changes in
New York City Air Quality while using machine learning models for possible forecasts
of Nitrogen Dixoide(NO2) levels throughout the atmosphere.

There are a multitude of factors that often contribute to the general air quality and pollution levels 
throughout a city. The current indicators for this project mostly consider traffic volume as a major 
contributor to air pollution. 

# General Trends and Map Overview 

We can begin by mapping historical NO2 levels by Community Districts and aggregating by the average level
in a 12-month period. This could help to assess any changes in NO2 and emerging patterns within our data.

The following procedure creates a choropleth map of NYC with respect to time and is available here:

[Change in NO2 Levels in NYC from 2008-2022](https://tinyurl.com/2e3m8779 )


# Machine Learning Models

## K-Means Clustering

Clustering multi-polygons with varying levels of Nitrogen Dioxide in 2020 produced the following clusters: 

![kmeans_NYC_2020](https://github.com/halaway/nyc-air-quality-analysis/assets/31904474/a2e7c14d-9304-4fd0-a389-8178c4e73d2f)

However, focusing only on our data from 2010, we can create 10 clusters for grouping Community Districts based on 
average NO2 levels and an aggregation of Traffic Volume per locale. 

This creates the following clusters: [Available Here](https://olive-susana-62.tiiny.site/) 

![Kmeans NYC 2010]<img width="878" alt="Screen Shot 2023-11-18 at 12 39 38 AM" src="https://github.com/halaway/nyc-air-quality-analysis/assets/31904474/f1b5429e-9136-4555-a7bd-445f555e0227">




