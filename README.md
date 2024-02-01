# Employee Salaries Analysis

This repository contains an analysis of employee salaries dataset, exploring various aspects such as data cleaning, exploration, visualization, and insights derived from the analysis.

## Dataset Overview

The dataset provides information about employee salaries, job titles, and related details. During the data cleaning process, several columns were dropped for various reasons, including lack of analytical value, empty or constant values, and absence of meaningful information. The columns dropped are:
- 'Id'
- 'Notes'
- 'Agency'
- 'Status'
- 'Benefits'

## Data Exploration

The dataset was explored to understand its structure, and basic statistics were calculated for numerical columns such as 'BasePay', 'OvertimePay', 'OtherPay', and 'TotalPay'. Missing values in 'BasePay' were filled with the mean, and other missing values were appropriately handled.

## Data Visualization

Histograms were created to visualize the distribution of salaries ('TotalPay'), providing insights into the overall salary structure. Additionally, pie charts were utilized to represent the proportion of employees in different departments, assuming the existence of a 'Department' or another relevant column.

## Grouped Analysis

The data was grouped to analyze summary statistics for different groups. An example was provided where the dataset was grouped by 'Year' to compare average salaries over time.

## Column Insights

- The 'Id' column was dropped as it lacked analytical value and did not contribute to insights or patterns.
- 'Notes' and 'Benefits' columns were removed due to the absence of data, providing no meaningful information.
- 'Agency' and 'Status' columns were dropped because of constant values or lack of information, respectively.

## Simple Correlation Analysis

The correlation between 'TotalPay' and 'OtherPay' was explored. If you encounter issues related to data types, ensure that the columns involved are of numeric types. The analysis included handling non-numeric values and checking the correlation coefficient.

## Recommendations

- Further exploration and analysis can be conducted based on specific business questions or goals.
- Consideration should be given to the specific nature of missing data and the impact on analyses.
