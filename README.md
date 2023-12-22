# Storytelling with Data: Obesity Trends in the US

## Overview

This project focuses on storytelling with data using the "Nutrition, Physical Activity, and Obesity" dataset published by the Centers for Disease Control and Prevention (CDC). The dataset contains information on the diet, physical activity, and weight status of American adults, collected from the Behavioral Risk Factor Surveillance System.

## Dataset Link: 

https://chronicdata.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data


## Dataset Cleaning (ETL Process)

- **Data Cleaning:**
  - Removed unnecessary columns containing footnotes, confidence limits, and redundant information.
  - Merged and renamed columns for clarity.
  - Filtered out rows with insufficient sample size or irrelevant questions.
  - Created new columns for numeric values and rounded up decimal percentages.

- **Data Categorization:**
  - Used filters to categorize data by age, gender, income, race, education, and overall.

## Visualizations: Using Tableau and PowerBI

**1. Top 5 States with the Highest Count of Obese Adults**
   - Bar chart depicting Nebraska, Florida, Kansas, Minnesota, and Maryland as the top 5 states with the highest obesity counts.

**2. Number of US Adults with Obesity: Classified by Age**
   - Tree map illustrating the distribution of obese adults across six age categories, with the highest count among those aged 65 and over.

**3. Top 5 States with the Highest Count of Obese Adults: Classified by Age**
   - Stacked column chart combining state and age categories, highlighting population distribution in the top 5 states.

**4. Number of US Adults with Obesity: Male vs. Female**
   - Pie chart showing the percentage distribution of obesity among adult men and women, with women having a higher count.

**5. Trend of Obesity in US Adults (2011-2019)**
   - Line chart representing the trend in obesity counts over the years, showing relatively consistent annual figures.

**6. Number of Obese US Adults Categorized by Race/Ethnicity**
   - Heat map showcasing the count of obese adults based on race/ethnicity, with Non-Hispanic White adults having the highest count.

## Summary

The project involved extensive data cleaning and transformation to create meaningful visualizations. The focus was on representing the impact of obesity across diverse demographic categories. While the dataset provided valuable insights, the conclusions drawn should be considered in light of the sample size limitations.

