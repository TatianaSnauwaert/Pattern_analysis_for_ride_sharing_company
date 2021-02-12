# Pattern_analysis_for_ride_sharing_company
## Data collection and storage project from Practicum by Yandex

### Goal

Prepare a report for Zuber, a new ride-sharing company that's launching in Chicago, to identify patterns that determine passenger preferences and the impact of external factors on rides.

### This project's repo includes the following files:

- SQL part of the project (Pattern_analysis_for_ride_sharing_company_part_1.pdf);
- The project's jupyter notebook (Pattern_analysis_for_ride_sharing_company_part_2.ipynb);
- A pdf format of the notebook (Pattern_analysis_for_ride_sharing_company.pdf);
- Input data (project_sql_result_01.csv, project_sql_result_04.csv, project_sql_result_07.csv);
- Project description from Practicum (SQL_project_description.pdf).

### This project includes the following steps:

1. Descriptive statistics;
2. Data Preprocessing: data type change, missing values and duplicates check;
3. EDA: top neighborhoods in terms of drop-off locations and market competition analysis;
4. Statistical hypothesis testing.

### Based on the analysis we have come to the following conclusions:

1. The "Loop" neighborhood is the most popular one - almost a quarter of all taxi rides end there. The second biggest neighborhood is "River North" - around 20% of rides end there, the 3rd and 4th are "Streeterville" and "West Loop", respectively. The rest of the top 10 Chicago neighborhoods account for 25% of all taxi rides;

2. The market of taxi services is quite competitive - we see almost a 100 different companies. The biggest company (in terms of amounts of trips) is "Flash Cab" - it occupies almost 15% of the market. All the larger companies together account for almost 75% of the market, while smaller companies (each occupying less than 1%) together account for almost a quarter of the market.

3. Next step was **statistical hypotheses testing**. We tested the following hypothesis: The average duration of rides from Loop neighborhood to O'Hare International Airport changes on rainy Saturdays.

Based on statistical tests, we have rejected the null - the average duration of a trip with "Good" weather_conditions is not the same as the average duration of a trip with "Bad" weather_conditions.

### The logbook of this project can be found [here](https://docs.google.com/spreadsheets/d/1SrGdReexaSEomJGS6yR6cRwJtHA_XqpprnLaE7B6Ayg/edit#gid=1671139843) (Intro to SQL tab).
Total time spent on the project: 5 hours with a daily average of 1.94 hours working for 3 days.
