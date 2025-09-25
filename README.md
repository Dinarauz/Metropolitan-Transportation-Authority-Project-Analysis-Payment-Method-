# MTA Transit Payment Method Analysis
![MTA_NYC_Logo_Black](https://github.com/user-attachments/assets/91752e2f-6eae-4ac9-b145-9b42c74c031f)

Data Analysis of NYC's Transportation Payment System Transition (2020 - 2024)

**Executive Summary:**
Analyzede 2.7 million MTA Transit records to understand the shift from MetroCard to OMNY payment systems across NYC. Built interactive dashboards showcasting payment adoption patterns by borough, fare class, and demographic groups during teh critical transition period.

**Key Findings:**
-OMNY usage grew from 536K to 12.7M riders, overtaking MetroCard by 2024 and marking a complete transformation in NYC transit payment behavior.

**Business Problem:**
**Industry Challenge:**
-NYC's Metropolitan Transportaiton Authority needs to understand the adoption of their new contactless payment system (OMNY) launched in May 2020, while managing the phase-out of lagacy MetroCard infrastructure.

**Analysis Objectives:**
-**Payment System Transition:** Track MetroCard vs OMNY adoption across 4+years
-**Demographic Analysis:**
**Interactive Dashboard:**
-https://public.tableau.com/app/profile/dinara.ibotova/viz/MTAproject_17455507165240/Dashboard1?publish=yes

**Raw Data:**
https://data.ny.gov/Transportation/MTA-Subway-Hourly-Ridership-2020-2024/wujg-7c2s/about_data

**Project Objectives:**
-Compare MetroCard vs OMNY usage from 2020 - 2024 (OMNY first implemented in May 2020)
-Explore different fare class categories (Full Fare, Students, Seniors, etc)
-Break down ridership by NYC borough to uncover geographic trends.
-Created an Interactive Panel so less visible data can be seen better, such as Staten Island was crushed in the Seaborn visualization
-Build an interactive Tableau Dashboard to make key insights easy to explore.

**Tools Used:**
- **Python (pandas, numpy, seaborn, matplotlib, requests, panel)** – for data cleaning, analysis, and visualization.
   -Grouped the data, used Pivot tables
- **Jupyter Notebook** for organizing and running the analysis.
- **Tableau** – for interactive dashboard development and visualization **Tableau Public**

**Key Findings from the NYC MTA Ridership Analysis (2019–2024):**
-Since implementing the OMNY payment method, OMNY usage has increased from 536K riders in 2020 to more than 12.7M in 2024, showing widespread adoption of the contactless fare payment method.
-By 2024, OMNY caught up and overtook MetroCard in total ridership, marking a turning point in rider behavior towards switching to the contactless system.
-MetroCard ridership peaked in 2022 (16.8M) but dropped each year after, ending at 11.1M in 2024, reflecting the gradual decrease of MetroCard fare systems.
-Discounted fare categories (e.g., Seniors, Students, Fair Fare) are still heavily used via MetroCard, likely due to slower adoption of OMNY to those groups.
-Compared to other Boroughs, Manhattan has the highest usage of OMNY full Fare, followed by Brooklyn, and Queens has slightly more usage of OMNY vs Metrocard.
-Staten Island and Bronx still leaned more heavily on MetroCards than OMNY.

**Pandemic impact:**
-Ridership dropped in 2020 due to COVID-19
-MetroCard usage bounced back strongly in 2021, while OMNY kept growing steadily after.
