# Uber Analysis

## Overview
The Uber Analysis Jupyter Notebook provides an in-depth analysis of Uber ride data for the year 2016 in multiple geographical locations, including the USA, Sri Lanka, and Pakistan. The dataset includes information about the start and end dates, categories of rides (business or personal), start and stop locations, miles traveled, and the purpose of each ride.

## Libraries Used
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- datetime
- time

## Dataset
The dataset consists of 1156 rows and 7 columns, containing information about Uber rides. Initially, the columns had asterisks in their names, which were removed during the data cleaning process.

## Data Cleaning
Data cleaning involved removing null values, changing column data types, and handling missing values. The 'PURPOSE' column, which had significant missing values, was filled using the forward fill method. Additionally, the 'START_DATE' and 'END_DATE' columns were converted to datetime data type.

## Data Analysis
**General Information**

- The dataset contains 1155 non-null entries.
- The columns include 'START_DATE', 'END_DATE', 'CATEGORY', 'START', 'STOP', 'MILES', and 'PURPOSE'.
- The total miles range from 0.5 to 12204.7, with an average of 21.12 miles.

**Category Analysis**

- The majority of rides are categorized as Business (1078), while only a few are classified as Personal (77).

**Start and Stop Locations**

- Cary is the most frequent start and stop location, followed by Unknown Location, Morrisville, Whitebridge, and Islamabad.

**Miles Analysis**

- The majority of rides cover distances between 2 and 10 miles.

**Purpose Analysis**

- Most rides are for Meeting purposes, followed by Meal/Entertainment and Errand/Supplies.

**Time Analysis**

- The average time for a trip is approximately 23 minutes.

**Monthly Analysis**

- December has the highest number of bookings, possibly due to the holiday season.

**Round Trip Analysis**

- Most rides are not round trips.

**Purpose and Category Comparison**

- Business trips dominate across various purposes, with Commute, Charity, and Moving being the only categories for Personal trips.

## Conclusions
The Uber analysis provides valuable insights into ride patterns, distances, and purposes. Key findings include a business-oriented user base, peak bookings in December, and popular start and stop locations. Understanding these patterns can help optimize service availability and cater to user preferences.
