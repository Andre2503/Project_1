# Data Analytics Bootcamp Project: World Happiness Report Analysis (2012-2022)

## Introduction

This repository contains code, images, datasets, and a presentation used for analyzing the World Happiness Report from 2012 to 2022. The aim was to identify trends and shifts in various metrics over time, with a specific focus on the changes that occurred from 2020 onwards, possibly due to the COVID-19 pandemic.

### Repository Contents

- `.gitignore`: Git ignore file to exclude unnecessary files from the repository.
- `Group 1 presentation - Final.pptx`: The final presentation outlining our findings.
- `Resources/`: 
  - `depression-rates-by-country-2023.csv`: Dataset containing depression rates by country for 2023.
  - `Mortality_COVID_19.csv`: Dataset containing COVID-19 mortality rates.
  - `WHR_2023.csv`: Dataset from the World Happiness Report for the year 2023.
- `Source_Code/`: 
  - `WHR_Analysis.ipynb`: This Jupyter Notebook includes the code used to generate plots and conduct the statistical analysis.

## Key Focus Areas

- Happiness Score
- Healthy Life Expectancy
- GDP per Capita
- Social Support

## Tools and Libraries Used

- Python
- Pandas
- Matplotlib
- Stats
- Geopandas (via Geopapy API)

## Features

1. **Basic Statistical Analysis**: Calculation of mean, median, variance, and standard deviation for all the years and key metrics of focus.
2. **Country Performance**: Analysis of top and bottom performing countries based on their Happiness Scores.
3. **Linear Regression**: Conducted linear regression analysis to find correlations between metrics.
4. **Country-Specific Analysis**: Plotted graphs specifically for Australia to study trends in happiness metrics.
5. **COVID-19 Impact**: Used Johns Hopkins database to correlate World Happiness metrics with COVID-19 mortality rates.
6. **Mental Health Correlation**: Merged data from 'Our World in Data' to study the correlation between depression rates and happiness scores.
7. **Geographical Plotting**: Used Geopapy API for geographical plotting of countries based on happiness and depression metrics.

## Findings

- **Global Trends**: A slight boost in happiness score was observed in 2020, particularly in countries with low GDP per capita.
- **Australia's Decline**: Despite improvements in GDP per capita and life expectancy, Australia's happiness score has been declining since 2013.
- **COVID-19 Impact**: Countries with the highest COVID-19 mortality rates tend to have high GDP per capita, and vice versa.
- **Mental Health**: No significant correlation was found between depression rates and happiness scores.

