# Train Transportation Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

## Project Overview
This Excel-based data analysis project explores commuter trends at the "Travel For All" train station from January to June 2025. The goal was to uncover usage patterns, demographic distributions, and operational insights to support better transportation planning and user experience.
Using a clean and interactive dashboard, this project summarizes key metrics derived from raw trip data, including passenger demographics, travel behavior, and station activites.


![Travel_for_all_Dashboard](https://github.com/user-attachments/assets/fdd37b63-a3b2-4769-8a1b-829be2ef6cff)



### Data Sources

This dataset was a simulated train station data provided for analytical purposes. It contains anonymized trip records, user demographics, and operational details for the period of January to June 2025.

Download here  <a href="https://github.com/Ebubejen/Travel_for_all_Excel-Project/blob/main/Travel_for_all%20Data%20Set.xlsx">Dataset</a>

###  Tools Used

- Microsoft Excel
  
  Data cleaning
  
  Pivot Tables & Pivot Charts for dynamic analysis
  
  Dashboard design using shapes, charts, and conditional formatting
  
  Slicers for interactive filtering

### Data Cleaning and Preparation  
In the intial data preparation phase, I performed the following tasks:

1. Removed duplicate rows and irrelevant entries (e.g. empty or cancelled trips)
2. Handled missing values by removing or imputing where necessary
3. Converted data types when needed for analysis

### Exploratory Data Analysis

Exploratory Data Analysis was performed to understand usage patterns, user demographics, and temporal trends in train station activity. Key areas of exploration included:

- User Demographics
   - Who are the users?
   - What is the gender distribution of users?
   - User age brackets
- Temporal Trends
   - Explored trip trends over time, visualized by month and week
   - Trip trends by time of the day. Most active time in the day
- Station Activity
   -  Top 10 Start Stations based on usage

### Data Analysis 

- Pivot table were used to Summaries data and compare catergories.
- Charts/Graphs like line graphs, pie charts,Column shart and many more were used to visualize trends and patterns.

### Results and Findings

The following insights were derived:

- User Demographics
   - Most of their users were Males and they are subscribers
   - The dominant age group range between 30-49 years, indicating a strong working-class commuter base.

- Trip Trends/Station Insights
   - High Trip count were recorded for early hours of the morning and evenings
   - The Top 10 Start Stations accounted for a large portion of all trips, showing station popularity and potential for infrastructure focus.
   - Daily trip frequency was shared almost evenly with Wednesday and Thursday being the highest and Sunday the lowest

- Performance Metrics
   - Total Revenue, Average Trip Duration, and Average Trips per Week were calculated and presented dynamically via slicers.
   - These KPIs allow decision-makers to interact with the dashboard and view performance across time and user segments.

### Recommendations

Based on the analysis, I recommend the following actions:

- Since the majority of users fall between ages 30–49, optimize train schedules and station services during peak commuting hours to cater to this demographic.
- The Top 10 start stations handle a significant portion of all trips. Invest in infrastructure upgrades, signage, and crowd control at these times.
- With Wednesday and Thursdays showing high usage, consider running more frequent trains or offering commuter-focused packages on those days.
- Since one gender is significantly underrepresented that is female users, consider marketing campaigns, safety initiatives, or feedback surveys to understand barriers and encourage balanced ridership.
- Use the monthly and weekly trends to improve train availability during known peaks (e.g., end-of-month rushes or holiday weekends).

### Limitations

1. The dataset only covers January to June 2025, which may not reflect seasonal variations or annual trends.
2. Revenue figures were estimated based on assumed rates, as actual fare data per trip or user was not provided.
3. While age and gender were available, other key demographics like income, occupation, or location were missing, which could have added more depth to user behavior insights.
4. The dashboard is based on static data, meaning it does not auto-refresh or account for real-time updates unless manually maintained.
5. The analysis is purely quantitative. No rider feedback or satisfaction data was available to supplement behavioral insights with user sentiment.

