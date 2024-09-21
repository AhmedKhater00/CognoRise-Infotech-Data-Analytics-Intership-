# Unemployment in India: Impact of Covid-19 Lockdown

## Introduction
This project investigates the impact of the Covid-19 lockdown on unemployment rates across various states in India. By analyzing historical data, the project aims to understand how the pandemic has affected employment opportunities and the labor market.

## Objectives
- To analyze changes in unemployment rates before and after the Covid-19 lockdown.
- To forecast future unemployment trends using statistical modeling.
- To visualize unemployment data geographically and temporally to identify patterns and disparities.

## Dataset
The dataset includes information on:
- **Region:** States in India
- **Date:** The date when unemployment rates were observed
- **Estimated Unemployment Rate (%):** The percentage of unemployed individuals in each state
- **Estimated Employed:** The percentage of employed individuals
- **Estimated Labor Participation Rate (%):** The labor force participation rate calculated as the number of people actively participating in the labor force divided by the total number of eligible individuals.
  
## Process Details
1. **Data Collection:**
   - Gathered data on unemployment rates, employment, and labor participation across Indian states during the Covid-19 lockdown.
3. **Data Preprocessing:**
   - Converted date formats and handled missing values.
   - Created additional features like 'Days' from the 'Date' column to facilitate analysis.
4. **Exploratory Data Analysis (EDA):**
   - Analyzed historical unemployment trends using line plots and bar charts.
   - Investigated pre-Covid and post-Covid employment rates.
5. **Modeling:**
   - Employed Polynomial Regression to forecast future unemployment rates.
   - Split the dataset into training and testing sets to evaluate model performance.
6. **Visualization:**
   - Created interactive maps using Folium to visualize unemployment rates by region.
   - Plotted various trends over time to illustrate the impact of Covid-19.

## Analysis
- Identified significant changes in unemployment rates pre- and post-Covid lockdown.
- Analyzed the average unemployment rate across different regions in India.
- Investigated trends in labor participation rates over time.

## Key Insights 🌟
- The unemployment rate significantly increased post-Covid, highlighting the economic impact of the lockdown.
- Certain regions experienced more drastic changes, indicating regional disparities in employment opportunities.
- Forecasts suggest ongoing challenges in unemployment rates as recovery progresses.

## 📊 Visualization
- Line charts showing unemployment rates over time.
- Bar charts depicting average unemployment rates by region.
- Choropleth maps illustrating regional unemployment distribution.

## Tools & Techniques Used
- File Name: Unemployment_Rate_upto_11_2020.xlsx

## Tools & Techniques Used
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn, Folium
- **Modeling:** Scikit-learn (Linear Regression, Polynomial Regression)
- **Data Preprocessing:** Handling missing values, date formatting

## Results of Data Analysis Process

## Data Overview
- The dataset covers unemployment rates across all Indian states from January 2020 to November 2020.
- Key features include unemployment rates, employment rates, and labor participation rates.

## Descriptive Statistics
- **Unemployment Rate:** The average unemployment rate increased from approximately 7% pre-Covid (January 2020) to over 23% post-Covid (April 2020).
- **Labor Participation Rate:** The labor participation rate showed a decline during the lockdown period, indicating reduced workforce engagement.

## Trends Over Time
### Pre-Covid vs. Post-Covid Analysis
- Average unemployment rates before the lockdown were significantly lower compared to the rates observed during and after the lockdown.
- A noticeable spike in unemployment rates was observed in April 2020, coinciding with the nationwide lockdown.

## Regional Analysis
- Certain states (e.g., Maharashtra, Tamil Nadu) exhibited higher unemployment rates compared to others (e.g., Bihar, Uttar Pradesh).
- The average unemployment rate varied significantly among states, with some regions facing more severe impacts.

## Visualizations
- **Line Plots:** Showed trends of unemployment rates over time, with clear increases during the lockdown.
- **Bar Charts:** Illustrated average unemployment rates by region, highlighting disparities.
- **Choropleth Maps:** Visualized unemployment distribution across states, making regional differences evident.

## Modeling Results
### Polynomial Regression Model
- The model effectively captured trends in unemployment rates, with a mean squared error (MSE) of approximately **134.13**.
- Future forecasts indicated that unemployment rates may remain elevated in the coming months, suggesting a slow recovery.

## Conclusion
The project provides insights into the effects of the Covid-19 pandemic on unemployment in India, highlighting both immediate impacts and potential future trends. Through data analysis and visualization, the findings can inform policymakers and stakeholders about the ongoing challenges in the labor market.

## Contact
For inquiries or collaboration opportunities, please reach out with me:

- **Name:** Ahmed Khater
- **Email:** [khatermedo664@gmail.com]
- **LinkedIn:** [Ahmed Khater](https://www.linkedin.com/in/ahmed-khater-1bb2a324a)
