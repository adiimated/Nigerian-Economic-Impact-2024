# Nigerian-Economic-Impact-2024

## Challenge Background

The Nigerian economy has experienced a significant surge in prices across various sectors, from daily commodities to services and products. This rapid change has impacted living conditions across different states, prompting a detailed analysis of key economic pillars such as incomes, expenditures, and savings capabilities of citizens.

## Goal of the Project

This project aims to provide a clear and actionable overview of the economic impact of price surges in Nigeria, facilitating informed decision-making and policy development.

## Data Collection and Indicators

Data has been collected on various indicators essential for analyzing price surges in Nigeria. The detailed tracking of these indicators can be found in our [Indicators/Features Tracker](https://github.com/adiimated/Nigerian-Economic-Impact-2024/tree/main/data%20collection/feature%20tracker).

Key Achievements:

* Data collection completed for multiple indicators.
* Comprehensive tracking of metrics such as government expenditure, trade openness, GDP, unemployment rate, oil production, inflation rate, exchange rate, and more.
* Data sourced from reputable databases like CBN, World Bank, NBS, and others.

## Data Preprocessing

Preprocessing Steps

1. Load Data: Load the transposed dataset from a CSV file.
2. Convert 'Year' Column: Convert the 'Year' column to datetime format and set it as the index.
3. Identify Columns Starting at 1985: Identify columns that have their first value starting at 1985.
4. Separate Datasets: Separate the dataset into two parts: one starting from 1985 and the other not starting from 1985.
5. Save Separated Datasets: Save the separated datasets to respective CSV files.
6. Clean Dataset Starting from 1985: Filter out rows with missing values before 1985 and save the cleaned dataset.
7. Handle Missing Values for Dataset Starting from 1960: Use backward fill method to handle missing values and save the cleaned dataset.

## Merging Process
Datasets were merged based on their starting year:

- **1950 Onwards**: `purchasingPower_processed.csv`
- **1960 Onwards**: Various datasets including consumer prices, OPEC crude oil prices, food import/export data, etc.
- **1980 Onwards**: Current account balance, exports of goods, population, agriculture, etc.
- **1990 Onwards**: Government GDP, unemployment rate, exchange rate volatility, etc.
- **2000 Onwards**: Consumer price index, government expenditure, fiscal balance, etc.
