# US Flights Delayed Analysis

## Project Overview 
- Flights delays create operational bottlenecks for airlines and severe friction for travelers. The end-to-end data project analyzes a dataset of 5,000 US flights to identify risk factors for departure delays.
- I utilized **Python** to extract, clean, and engineer the dataset, and **Power BI** to develop an interactive dashboard for stakeholder reporting.

## Business Objective
To determine which days of the week, airline, and origin airports experience a higher frequency of departure delays, allowing stakeholders to anticipate disruptions and passengers to make data-informed travel choices.

## Tech Stack
* **Data Engineering (ETL):** Python (Pandas, Jupyter Notebook)
* **Data Visualization & BI:** Power BI (DAX, Map visualizations, Interactive Dashboards)
* **Dataset:** 5,000 US domestic flight records.

## Methodology
1. **Python Data wrangling:**
  * Converted textual departure strings into 'datetime64' objects.
  * Engineered a time-delta analysis to flag flghts delayed by > 15-minutes.
  * Exported the processed data pipeline into a clean CSV.
2. **Power BI Dashboarding:**
  * Developed custom DAX measures to calculate dynamic delay percentages.
  * Built data visuals to identify bottlenecks.
  * Implemeted interactive cross-filtering for airline-specific deep dives.

## Key insights
* **Peak Disruption Risk:** **Sundays (23.4%)** and **Fridays (22.6%)** experience the highest rates of departure delays across the board.
* **Maximum reliability:** **Tuesday** is historically the safest day to travel, with the delay likelihood dropping to just **15.4%**.

## Repository Contents
* 'US_Flight_Delays_Analysis.ipynb': The Python script detailing the ETL and EDA process.
* 'cleaned_US_flights.csv': The finalized dataset powering the dashboard.
* 'US_FLIGHT_DELAY_ANALYSIS_DASHBOARD.pbix': The interactive Power BI dashboard file.
* Power BI dashboard visual represention:


https://github.com/user-attachments/assets/d0de511f-943f-4299-8371-ac3c32c82d38

<img width="1077" height="547" alt="Screenshot 2026-09-21 110656" src="https://github.com/user-attachments/assets/afa02e7d-330a-4aaf-bb26-4949bb7d7117" />


