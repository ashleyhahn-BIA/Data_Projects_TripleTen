# Project 2: A/B Test Analysis for Food Delivery Startup (Zuber Ride-Sharing Analysis)

## Project Overview
The objective of this project was to analyze ride-sharing data for Zuber, a new ride-sharing company in Chicago. The goal was to identify patterns in passenger behavior, understand taxi company competition, and evaluate the impact of weather conditions—specifically rain—on ride duration from the city center to the airport.

The project involved querying a SQL database containing taxi trip data, company information, neighborhood details, and weather records. Hypotheses were tested using structured queries and aggregations to uncover insights about ride patterns under different weather and time conditions.

## Business Questions Answered
- Which taxi companies are dominant in Chicago during November 2017?
- How does the number of rides differ for companies with "Yellow" or "Blue" in their names?
- What share of rides is captured by Flash Cab and Taxi Affiliation Services versus other companies?
- Does rainy weather impact ride duration from the Loop to O'Hare International Airport on Saturdays?

## Key Tasks and Methodology
- **Exploratory Data Analysis**:
  - Aggregated and compared ride counts across companies between specific date ranges.
  - Identified market leaders and compared ride volume between major companies and others.
- **Weather Impact Analysis**:
  - Created a binary weather classification (`Good` vs `Bad`) based on descriptions containing "rain" or "storm."
  - Merged ride and weather data on hourly timestamps.
  - Filtered for rides originating from the Loop (ID: 50) and ending at O'Hare Airport (ID: 63).
  - Focused specifically on Saturdays to evaluate potential weather effects on trip duration.
- **SQL Techniques Used**:
  - Aggregations (COUNT, GROUP BY)
  - CASE WHEN statements for weather categorization
  - JOIN operations across multiple tables
  - Filtering using LIKE statements and date functions

## Key Findings
- **Flash Cab** and **Taxi Affiliation Services** emerged as top competitors in November 2017.
- Ride patterns showed significant dominance by a small number of companies.
- Rainy weather (`Bad` conditions) increased the median duration of rides from the Loop to O'Hare International Airport on Saturdays compared to rides taken during `Good` weather conditions.

## Tools Used
- SQL (PostgreSQL)
- Data analysis using Google BigQuery / TripleTen's cloud SQL environment

## Deliverables
- SQL queries for data retrieval and analysis
- Data cleaning and transformation scripts
- Final insights presented in query results and pivoted tables

## Project Link
👉## Project Files
- [Exploratory Data Analysis SQL](./exploratory_analysis.sql)

