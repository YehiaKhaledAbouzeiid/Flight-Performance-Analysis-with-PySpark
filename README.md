# Airline Flight Analysis with PySpark

## Overview

This project utilizes PySpark to analyze and explore information from the airlines1.csv dataset, uncovering insights into flight performance, delays, cancellations, and other interesting trends.

## Key Features

- Reads and registers the airlines1.csv data as a Spark DataFrame.
- Performs a variety of SQL queries to analyze the data, including:
  - Counting rows and finding averages.
  - Grouping data by origin, year, and month.
  - Calculating on-time performance, cancellations, and diversions.
  - Ranking destinations based on various metrics.
  - Determining top performing routes based on average speed.
- Presents the results visually through Spark show() methods.

## Case Studies

1. **Year-wise On-Time Performance:**
   - Analyzes flight performance across years, calculating total flights, on-time flights, cancellations, and diversions.

2. **Origin City Analysis:**
   - Examines flight data for each origin city, including total flights, on-time flights, cancellations, and diversions.

3. **Ranking Top Origin-Destination Pairs:**
   - Finds the top origin-destination pairs based on the number of flights.

4. **Average Speed Calculation:**
   - Determines the average speed of flights based on flight time and distance.

## Additional Notes

- This project focuses on exploring the airlines1.csv dataset. You can adapt the code to analyze other datasets related to airline flights.
- The SQL queries demonstrate different ways to manipulate and aggregate data using Spark SQL. You can explore further queries to uncover deeper insights.

## Next Steps

- Analyze additional columns within the dataset (e.g., weather conditions, carrier details).
- Create visualizations using libraries like matplotlib or seaborn.
- Develop machine learning models to predict flight delays or cancellations.

