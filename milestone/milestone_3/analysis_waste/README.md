# Data Analysis using CSV Files

## Description

This project involves the analysis of data from three CSV files containing information on waste production in various countries and regions. For each file, three types of estimates were considered: Retail estimate, Household estimate, and Food service estimate. Detailed analysis was conducted, including data type checking, data processing and cleaning, as well as statistical analysis.

## Used Files

1. **Retail Data:** [`retail_food_waste.csv`](./milestone/milestone_3/analysis_waste/retail_food_waste.csv)

   - Structure: Region, M49 code, Country, Retail estimate (kg/capita/year), Retail estimate (tonnes/year), Confidence in estimate

2. **Household Data:** [`household_waste.csv`](./milestone/milestone_3/analysis_waste/household_waste.csv)

   - Structure: Region, M49 code, Country, Household estimate (kg/capita/year), Household estimate (tonnes/year), Confidence in estimate

3. **Food Service Data:** [`food_service_waste.csv`](./milestone/milestone_3/analysis_waste/food_service_waste.csv)
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

11. **Food Service Waste Analysis:**

    - The analysis focuses on the geographical distribution of waste emissions, suggesting potential variations in waste management efficiency among countries. Changes in country numbers within specific ranges hint at evolving trends influenced by food consumption strategies. Additionally, differences in the legislative landscape highlight varying policy needs for waste management from food services. This comprehensive assessment provides insights into the complex dynamics of waste management practices and the potential influence of regional strategies and policies.

12. **Food Service Waste Graph:**

    - The graph illustrates the diverse distribution of food service expenditures across various countries. Notable differences in bin sizes indicate variations in consumption levels, with the United States leading in expenditures. Germany and Denmark, as well as Poland and Canada, exhibit similarities in their consumption patterns. Ukraine stands out with a substantial level of food service expenditures. These observations highlight the heterogeneous nature of food service consumption habits, prompting further exploration of the factors contributing to these differences.

13. **Household Waste Analysis:**

    - The analysis highlights the varying levels of household waste estimates across countries. Poland and the USA exhibit similarities in their estimates, while Germany and Ukraine show comparable, moderately elevated values. Canada and Denmark, however, surpass others, indicating higher estimates of household waste per capita per year.

14. **Retail Waste Analysis:**
    - The graph depicts the distribution of retail waste estimates (kg/capita/year) across selected countries. Germany shows the lowest retail waste, while Canada and Poland exhibit moderate values. The United States and Ukraine have slightly higher retail waste, but Denmark stands out with significantly higher levels. Denmark's unique profile is influenced by factors such as limited local production, a substantial amount of imported perishable goods, and higher average affluence leading to increased food waste. Overall, the graph highlights diverse patterns in retail waste, reflecting variations in consumption habits and waste management practices among the countries.

## `Possible Alternative Approaches`

1. **Machine Learning Models:**

   - Explore models like Random Forest or Gradient Boosting for predictive modeling.

2. **Robust Regression:**

   - Consider robust regression techniques like Huber regression to address potential outliers.

3. **Advanced Geospatial Techniques:**
   - Utilize advanced geospatial analysis techniques for deeper insights into regional waste distribution patterns.

## Usage

1. Download the files [`retail_food_waste.csv`](./milestone/milestone_3/analysis_waste/retail_food_waste.csv), [`household_waste.csv`](./milestone/milestone_3/analysis_waste/household_waste.csv), and [`food_service_waste.csv`](./milestone/milestone_3/analysis_waste/food_service_waste.csv).
2. Run the script to perform data analysis and visualization.

## Requirements

| Package      | Version |
| ------------ | ------- |
| `python`     | 3.x     |
| `pandas`     | 2.1.x   |
| `matplotlib` | 3.8.x   |
| `seaborn`    | 0.13.x  |
| `numpy`      | 1.26.x  |
