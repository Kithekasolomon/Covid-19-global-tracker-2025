# Covid-19-global-tracker-2025
# COVID-19 Global Data Tracker Project

## Overview

This project analyzes and visualizes global COVID-19 data using Python's `pandas`, `matplotlib`, and `seaborn` libraries. It fulfills an assignment to load, explore, and analyze a dataset, perform statistical computations, and create visualizations. The dataset used is the **WHO COVID-19 Global Data** CSV, which provides daily cumulative counts of confirmed cases, deaths, and other metrics by country from January 2020 to August 2025.

The script (`covid19_global_tracker.py`) performs the following tasks:
1. **Data Loading and Exploration**: Loads the dataset from the WHO URL, displays initial rows, checks data types and missing values, and cleans the data.
2. **Basic Data Analysis**: Computes summary statistics, groups data by WHO region and country, and identifies patterns.
3. **Visualizations**: Creates four plots (line chart, bar chart, histogram, scatter plot) to visualize trends, comparisons, distributions, and relationships.
4. **Findings**: Summarizes insights, such as regional disparities and declining case trends in 2025.

## Dataset

- **Source**: World Health Organization (WHO) COVID-19 Global Data
- **URL**: [https://covid19.who.int/WHO-COVID-19-global-data.csv](https://covid19.who.int/WHO-COVID-19-global-data.csv)
- **Description**: Contains ~1.2 million rows with columns like `Date_reported`, `Country`, `WHO_region`, `New_cases`, `New_deaths`, `Cumulative_cases`, `Cumulative_deaths`.
- **Date Range**: January 2020 to August 2025 (updated regularly by WHO).
- **Note**: The script dynamically downloads the CSV. For offline use, download the file manually and modify the script to use `pd.read_csv('local_file.csv')`.

## Requirements

- **Python Version**: 3.8+
- **Libraries**:
  - `pandas`: For data manipulation
  - `matplotlib`: For plotting
  - `seaborn`: For enhanced plot styling
  - `requests`: For downloading the dataset
- Install dependencies:
  ```bash
  pip install pandas matplotlib seaborn requests