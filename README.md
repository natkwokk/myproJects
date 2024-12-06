COVID-19 Data Analysis Using ElasticSearch
Authors: Nathan Kwok, An Nguyen, Tyler Trinh, Hans Eron Valderama
Department of Information Systems, California State University, Los Angeles

Overview
This project utilizes ElasticSearch to analyze and visualize COVID-19 data collected in the U.S. The dataset, sourced from the CDC and other organizations, contains records from March 7, 2020, to October 12, 2024. The goal is to identify trends and insights such as:

States with the highest and lowest cases per year.
Age ranges and demographics most affected.
Seasonal variations in cases and hospitalizations.
Motivation
COVID-19 had a profound impact on individuals and communities across the globe. Understanding the patterns of its spread and its effects on different demographics is crucial for public health policy and future preparedness.

Dataset
Source: CDC's COVID-NET and related systems.
Details: Includes state, season, age category, sex, race, weekly rates, and cumulative rates.
Size: 11 MB.
Methodology
Data Processing:
Data imported into Elastic Cloud.
Graphs and visualizations created using Kibana.
Machine Learning:
Regression analysis performed using ElasticSearch's ML features.
Feature importance measured for variables affecting weekly COVID-19 case counts.
Key Findings
States: Top 5 states with the highest reported cases.
Seasons: COVID-19 peaks were observed during summer and winter months.
Age Ranges: Adults (18+) were most commonly affected.
Race: African-American communities reported higher case counts, likely due to systemic factors.
Weekly Hospitalizations: Trends indicated higher rates during winter.
Prediction Accuracy: R-squared value of 0.757 demonstrates reliable predictions.
Visualizations
The following visual tools were used to analyze the data:

Bar graphs (weekly trends).
Pie charts (age ranges).
Time-series graphs (yearly case distribution).
Tools & Technologies
ElasticSearch: For data storage and analysis.
Kibana: For creating visualizations.
Elastic Cloud: Hosting platform.
References
Data and insights for this project were gathered from:

CDC COVID Data Tracker
Worldometer
Los Angeles County Department of Public Health
WHO COVID-19 Dashboard
Research studies on COVID-19 trends and impacts
Conclusion
The analysis underscores the importance of comprehensive data in understanding and mitigating the effects of pandemics. Factors like population density, healthcare access, and demographics play a significant role in case distribution. Public health efforts must focus on these disparities for improved preparedness and response.

