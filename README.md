# Crimes_in_India_PowerBI_Dashboard

## Project Overview

**Project Title**:  Crimes_in_India_PowerBI_Dashboard


This project focuses on analyzing crime data across different states in India. The project involves setting up a Power BI dashboard that visualizes crime statistics by category, state, and year. It leverages multiple chart types to provide insights into crime trends, top states with high and low crime rates, and category distributions.

## Objectives

1. **Year-Wise Crime Distribution**: Analyze the distribution of various crime categories for each year using a pie chart.
2. **State Crime Analysis**: Compare top 5 states with the highest crime rates for a selected crime category using a line graph.
3. **Crime Category Breakdown by State**: Display the breakdown of crime categories for a selected state using a pie chart.
4. **Crime Rate Comparison**: Identify states with high and low crime rates using area charts.
5. **Geographical Crime Distribution**: Visualize crime categories across Indian states on a map, with color-coded intensity based on crime count.

---

## Project Structure

### 1. **Dataset Setup & Cleaning**

- **Data Source**: Import the dataset containing crime data, structured with fields like `State`, `Crime Category`, `Year`, `Crime Count`, etc.
- **Data Cleaning**: Perform data cleaning steps to remove duplicates, handle missing data, and ensure data consistency.

### 2. **Data Exploration & Visualization**

The following Power BI visualizations were created to provide insights:

### 3. **Year-Wise Crime Distribution (Pie Chart)**

- **Objective**: Display the distribution of different crime categories (e.g., theft, assault, murder) for each year.
- **Chart Type**: Pie Chart
- **Fields Used**:
  - **Legend**: Crime Category
  - **Values**: Crime Count
  - **Filters**: Year
- **Insights**: Helps in understanding which crimes were more prevalent in a particular year.

### 4. **Top 5 States with Selected Crime Category (Line Graph)**

- **Objective**: Identify and visualize the top 5 states with the highest crime count for a selected crime category.
- **Chart Type**: Line Graph
- **Fields Used**:
  - **X-Axis**: State
  - **Y-Axis**: Crime Count
  - **Filters**: Crime Category (selectable)
- **Insights**: Displays trends and patterns in the crime rates for the top 5 states in a particular crime category.

### 5. **Selected State Crime Category Distribution (Pie Chart)**

- **Objective**: Show the distribution of crime categories for a selected state to understand which crimes dominate in that state.
- **Chart Type**: Pie Chart
- **Fields Used**:
  - **Legend**: Crime Category
  - **Values**: Crime Count
  - **Filters**: State (selectable)
- **Insights**: Visualizes how crime is distributed across different categories within a state.

### 6. **High Crime Rate States (Area Chart)**

- **Objective**: Identify and visualize the states with the highest crime rates.
- **Chart Type**: Area Chart
- **Fields Used**:
  - **X-Axis**: State
  - **Y-Axis**: Crime Count
  - **Filters**: High Crime Rate States
- **Insights**: Highlights states with significantly high crime counts.

### 7. **Low Crime Rate States (Area Chart)**

- **Objective**: Visualize states with lower crime rates.
- **Chart Type**: Area Chart
- **Fields Used**:
  - **X-Axis**: State
  - **Y-Axis**: Crime Count
  - **Filters**: Low Crime Rate States
- **Insights**: Focuses on states where crime rates are relatively low.

### 8. **Crime Category Distribution by State (India Map)**

- **Objective**: Geographically represent crime categories across different states in India.
- **Chart Type**: Map
- **Fields Used**:
  - **Location**: State
  - **Legend**: Crime Category
  - **Color Saturation**: Crime Count (light to dark color based on crime intensity)
- **Insights**: Offers a visual representation of how various crime categories are distributed across India, allowing for easy comparison.

---

## Analysis & Findings

1. **Yearly Crime Trends**: The pie chart reveals which crime categories were dominant in each year, showing shifts or trends in criminal activity.
2. **State-Level Insights**: The line graph allows identification of states with persistent or rising crime rates in a specific category.
3. **High & Low Crime Rates**: Area charts provide a clear contrast between states with high and low crime rates.
4. **Geographical Patterns**: The map highlights how different crime categories are spread geographically, helping to identify regional trends in crime.

---

## Conclusion

This Power BI dashboard offers a comprehensive view of crime data in India, enabling analysts to track crime trends, compare states, and identify hotspots for specific crime categories. It supports data-driven decision-making for law enforcement and policymakers.
