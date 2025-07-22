# Cyclistic Bike-Share Usage Analysis

This project is part of the **Google Data Analytics Capstone** on Coursera. I analyzed ride data from Cyclistic, a fictional bike-share company, to uncover behavioral differences between **casual riders** and **annual members**.

## Dataset
- Source: [Divvy Bike Share](https://divvybikes.com/system-data)
- Files used:
  - `Divvy_Trips_2019_Q1.csv`
  - `Divvy_Trips_2020_Q1.csv`
- Total Rows: ~365,000+

## Tools & Skills
- **R** for data cleaning, wrangling, transformation
- **ggplot2** for basic visualization
- **Tableau** for interactive dashboards
- **dplyr**, **lubridate**, **tidyverse**

## Data Cleaning Steps
- Removed nulls and ride durations < 0
- Converted datetime columns to proper format
- Created calculated fields (ride length, day of week)
- Merged and filtered inconsistent entries

**View the full R script and analysis** here: 
[firstProject.html – hosted on GitHub Pages](https://emilyz23.github.io/Cyclistic-Capstone/firstProject.html)

## Key Visualizations (Tableau)
- Average Ride Length by Day of Week & User Type
- Total Ride Count by Day of Week & User Type
- Total Ride Length by Day of Week & User Type
- Monthly Trends (Q1 & Q2, month 1 - 3)
  
View Tableau Dashboard: [(https://public.tableau.com/views/SharedBikesAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]

## Key Findings
- Casual riders take longer rides, mostly on weekends.
- Members ride shorter but more frequently during weekdays.
- Thursday sees the highest ride duration among casual users.

## Files Included
- `firstProject.Rmd` – RMarkdown for analysis
- `avg_ride_length.csv` – Aggregated cleaned output


