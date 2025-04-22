# Portfolio-Tableau
Repository focused on studies using the Tableau tool.

# 📊 ✈️ Airline Reviews Dashboard

![Demonstração](https://github.com/nicowirtzbiki/Portfolio-Tableau/blob/main/Airline%20Reviews%20Dashboard/reviews-report-video.gif)

https://public.tableau.com/app/profile/nicole.rocha.wirtzbiki/viz/ReportPortfolio/Dashboard1

## Overview
The Airline Reviews Dashboard is an interactive Tableau project designed to help British Airways monitor customer satisfaction and identify areas for improvement. The dashboard leverages passenger reviews collected between March 2016 and October 2023, covering several key experience metrics, such as Ground Service, Cabin Staff Service, Entertainment, Food and Beverages, Seat Comfort, and Value for Money.

By offering dynamic filtering options and visually engaging charts, this tool enables stakeholders to gain actionable insights and make data-driven decisions aimed at enhancing customer experience.

## Problem Statement
Airlines operate in a highly competitive market where customer satisfaction is a critical differentiator. This project was created to help British Airways understand how passengers from different backgrounds perceive their travel experience across various aircraft, continents, and service types.

By analyzing feedback provided by passengers from diverse regions, the goal is to uncover patterns in service perception, track satisfaction over time, and highlight opportunities for improvement in key service dimensions.

## Steps Followed
1. **Parameter Creation – "Pick a Metric":**
A parameter was created to allow users to dynamically select one of the key satisfaction metrics (e.g., Ground Service, Cabin Staff Service, etc.). This parameter is the core of the dashboard’s interactivity.

2. **Metric Selection Logic – Calculated Fields:**
For each metric option, calculated fields were built to return the selected value based on the user’s choice in the parameter. These fields are used in all visualizations to ensure they update accordingly.

3. **Dashboard Interactivity – Dynamic Titles and Visuals:**
Dynamic titles and chart labels were implemented using the selected metric. This ensures that every component of the dashboard reflects the current user selection, enhancing clarity and consistency.

4. **Filters Implementation:**
Filters for Date, Traveller Type, Seat Type, Aircraft, and Continent were added to provide detailed segmentation options and allow for deeper exploratory analysis.

5. **Layout Design:**
A clean and intuitive layout was created, with a horizontal KPI bar at the top and visualizations that provide complementary insights across country, time, and aircraft type.

## Visualization & Dashboard Development
The dashboard layout was carefully designed to maximize usability and clarity:

### Filters (left-side vertical bar):
- **Pick a Metric**: Choose one of the satisfaction metrics to analyze (e.g., Seat Comfort, Food and Beverages, etc.)

- **Month of Date**: Filter the date range (March 2016 – October 2023)

- **Traveller Type**: Select traveler category (Business, Couple Leisure, Family Leisure, etc.)

- **Seat Type**: Compare satisfaction across seat classes (Economy, Premium, First Class, etc.)

- **Aircraft**: Filter by aircraft model

- **Continent**: Explore regional differences

### KPIs (top horizontal bar):
Displays average scores for all metrics.

### Visualizations:
🌍 **Average ‘[Selected Metric]’ by Country**
A choropleth map that highlights satisfaction scores across countries served by British Airways.

📈 **Average ‘[Selected Metric]’ by Month**
A line chart showing how passenger satisfaction evolves over time.

🛫 **Average ‘[Selected Metric]’ by Aircraft**
Dual bar charts showing average rating and number of reviews per aircraft model.

All titles and labels update automatically based on the selected metric, offering a seamless and intuitive user experience.

## Business Impact
**Customer Experience Monitoring:** 
The dashboard allows British Airways to monitor how satisfaction changes over time and across customer profiles.
**Service Optimization:**
By highlighting low-performing aircraft or traveler categories, the company can make targeted service improvements.
**Global Insights:**
Regional analysis helps identify cultural or geographic trends in customer expectations and perceptions.

## ✅ Conclusion
The Airline Reviews Dashboard is a powerful tool for turning customer feedback into strategic insights. By transforming raw review data into clear, actionable visualizations, it supports British Airways in making informed decisions to elevate service quality and customer satisfaction. 🚀

