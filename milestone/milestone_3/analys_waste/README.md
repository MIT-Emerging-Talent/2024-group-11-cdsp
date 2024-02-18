# Data Analysis using CSV Files

## Description

This project involves the analysis of data from three CSV files containing information on waste production in various countries and regions. For each file, three types of estimates were considered: Retail estimate, Household estimate, and Food service estimate. Detailed analysis was conducted, including data type checking, data processing and cleaning, as well as statistical analysis.

## Used Files

1. **Retail Data:** `retail_food_waste.csv`

   - Structure: Region, M49 code, Country, Retail estimate (kg/capita/year), Retail estimate (tonnes/year), Confidence in estimate

2. **Household Data:** `household_waste.csv`

   - Structure: Region, M49 code, Country, Household estimate (kg/capita/year), Household estimate (tonnes/year), Confidence in estimate

3. **Food Service Data:** `food_service_waste.csv`
   - Structure: Region, M49 code, Country, Food service estimate (kg/capita/year), Food service estimate (tonnes/year), Confidence in estimate

## Data Analysis

1. **Check Data Types:**

   - Checked data types for each column in all CSV files.

2. **Data Cleaning:**

   - Values in the 'Retail estimate (tonnes/year)' column were cleaned from commas with subsequent conversion to a numeric format.

3. **Display First Rows:**

   - Displayed the first few rows of the 'Retail estimate (tonnes/year)' column for each CSV file.

4. **Grouping and Statistical Analysis:**

   - Data were grouped by 'Region', and statistical summaries were calculated for each group.

5. **Data Type of 'kg/capita/year':**

   - Checked the data type of the '\* estimate (kg/capita/year)' column.

6. **Unique Values of 'kg/capita/year':**

   - Displayed unique values of the '\* estimate (kg/capita/year)' column.

7. **Conversion to Numeric Format:**

   - Converted the '\* estimate (kg/capita/year)' column to a numeric format, ignoring errors.

8. **Grouping by Region:**

   - Data were grouped by 'Region', and statistical summaries were calculated for 'Household estimate (kg/capita/year)'.

9. **Grouping by Regions and Countries:**

   - Total waste production was calculated for each region.

10. **Percentage of Waste Production by Country:**
    - Calculated the percentage of waste production by each country within the region.

## Data Filtering and Charts

11. **Data Filtering by Regions:**

    - Used data filtering to select specific regions for further analysis.
    - Selected regions: Europe and North America.

12. **Charts for Each Estimate Type:**
    - Constructed charts for 'Retail estimate (tonnes/year)', 'Household estimate (tonnes/year)', and 'Food service estimate (tonnes/year)' in selected regions.

## Usage

1. Download the files `retail_food_waste.csv`, `household_waste.csv`, and `food_service_waste.csv`.
2. Run the script to perform data analysis and visualization.

## Requirements

- Python 3.x
- Libraries: pandas, matplotlib
