# Weather-Temperature-on-Health-Analysis

## Overview
This portfolio project explores the relationship between **weather conditions** and **human health metrics**. Using two Kaggle datasets (weather + patient health records), I merged them using a common **Date/Time** attribute and built an interactive **Power BI dashboard** to identify trends and correlations between environmental factors and vital signs.

The analysis focuses on how **temperature, humidity, wind speed, and dew point** may influence health indicators such as **heart rate, body temperature, and blood pressure**.

## Objectives
- Understand whether weather patterns correlate with changes in body vitals
- Identify which age groups show greater variability in heart rate and temperature response
- Provide insights that support climate-sensitive healthcare monitoring and prevention strategies

## Data Sources
- **Dataset 1 (Kaggle):** Weather dataset (temperature, humidity, wind speed, dew point, etc.)
- **Dataset 2 (Kaggle):** Patient health dataset (heart rate, body temperature, blood pressure, age, blood type, etc.)
- The final dataset was created by **merging both datasets** on a shared **Date/Time** field.


## Project Workflow
1. **Data Cleaning & Preparation**
   - Removed duplicates
   - Handled missing values
   - Standardized data types and ensured consistency for Date/Time joins

2. **Data Modeling**
   - Built a relational model in Power BI
   - Linked *Weather* and *Health* tables using the **Date/Time** attribute
   - Created measures/columns required for visuals and filtering

3. **Dashboard Development**
   - Created interactive visuals and slicers for exploration by age, blood type, and weather conditions
   - Designed pages to highlight relationships between environmental variables and vitals

## Key Visuals / Insights (High Level)
- **Heart Rate vs Age:** Middle-aged individuals (approximately 40–60) show higher variability; younger groups are more stable.
- **Body Temperature vs Weather Temperature (by Age):** Body temperature tends to fluctuate with changing weather temperature, with sensitivity varying by age group.
- **Blood Type Distribution:** Shows prevalence of blood types in the dataset, supporting deeper segmentation and trend comparison.

## Summary Findings
- Weather conditions influence human health metrics.
- Higher humidity and temperature can impact body temperature.
- Heart rate fluctuations may occur under varying wind speeds.
- Some age groups and blood types appear more sensitive to environmental changes.

## Tools & Technologies
- **Power BI Desktop** (Data model + Dashboard)
- **CSV dataset preparation**
- Optional: Excel / Power Query for cleanup steps (depending on workflow)

## Repository Contents
```text
/
├── merged_health_weather_data.csv          # Final merged dataset
├── merged_health_weather_final1.pbix       # Power BI dashboard file
├── Weather Temperature health final ppt.pptx  # Project presentation (optional)
└── README.md
