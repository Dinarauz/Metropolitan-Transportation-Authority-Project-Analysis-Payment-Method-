# MTA Transit Payment Method Analysis
![MTA_NYC_Logo_Black](https://github.com/user-attachments/assets/91752e2f-6eae-4ac9-b145-9b42c74c031f)

NYC MetroCard vs OMNY Transition Analysis (2020-2024)

Analyzed 2.7 million MTA transit records to track the shift from MetroCard to OMNY payment systems across NYC. Built interactive dashboards showing payment adoption patterns by borough and fare class during the transition period.

**Key Result:** OMNY usage grew from 536K to 12.7M riders (2,269% increase), overtaking MetroCard by 2024.

**Business Problem:**
NYC's MTA launched OMNY contactless payment in May 2020 while phasing out MetroCard systems. They hired us to understand adoption patterns across different demographics and geographic areas to optimize the transition.

**Data Pipeline:**
-Web scraped NYC Open Data API (50K+ records per month)
-Processed 2.7M transit records from 2020-2024
-Cleaned data: removed nulls, standardized columns, converted data types
-Mapped ridership by NYC borough and fare class

**Analysis & Visualization:**

-Time series analysis of payment method adoption
-Demographic segmentation by fare types (Full Fare, Students, Seniors)
-Geographic breakdown across 5 NYC boroughs
-Interactive Tableau dashboard for exploration

**Technical Implementation:**
-The complete analysis is available in the Jupyter notebook: https://github.com/Dinarauz/Metropolitan-Transportation-Authority-Project-Analysis-Payment-Method-/blob/main/MTA_project-2.ipynb

**Key Implementation Steps:**
-API data extraction from NYC Open Data (50K records per month)
-Data cleaning: null removal, column standardization, type conversion
-Time series analysis and geographic mapping
-Interactive visualizations using Panel for enhanced exploration

**Tools Used:**
- **Python (pandas, numpy, seaborn, matplotlib, requests, panel)** – for data cleaning, analysis, and visualization.
   -Grouped the data, used Pivot tables
- **Jupyter Notebook** for organizing and running the analysis.
- **Tableau** – for interactive dashboard development and visualization **Tableau Public**

**What I Found in the MTA Data (2020–2024):**
-OMNY went from 536K users in 2020 to 12.7M in 2024 - pretty much everyone switched to contactless payment
-OMNY finally passed MetroCard usage in 2024, which was the big turning point I was tracking
-MetroCard hit its peak in 2022 at 16.8M users, then dropped to 11.1M by 2024 as people moved away from it
-Seniors and students are still mostly using MetroCard. They haven't switched to OMNY as much as other riders
-Manhattan uses OMNY the most, Brooklyn is second, Queens is pretty balanced between both systems
-Staten Island and the Bronx still prefer MetroCard over OMNY

**COVID Effect:**
-Everything dropped in 2020 because of the pandemic
-MetroCard came back strong in 2021, but OMNY just kept growing steadily the whole time

**What This Means for MTA:** Looking at these patterns, MTA should probably:
-Focus OMNY outreach on seniors and students since they're still using MetroCard more. A lot of these groups get physical MetroCards through discount programs, so if MTA could work with schools and senior centers to distribute digital OMNY cards instead, that would probably speed up the transition
-Do more OMNY promotion in the Bronx and Staten Island where people are still using MetroCard
-We can use these usage trends to figure out when they can actually shut down the MetroCard system

**Interactive Dashboard:**
-https://public.tableau.com/app/profile/dinara.ibotova/viz/MTAproject_17455507165240/Dashboard1?publish=yes

**Data Source (Raw Data):**
https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-2020-2024/wujg-7c2s/about_data
