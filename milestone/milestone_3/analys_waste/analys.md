# Household Waste Estimates Dataset

## Description

### Origin of the Data

The dataset consists of estimates of household waste per country, sourced from the 2021 UNEP Food Waste Index Report. It provides information on household waste generation, categorized by region, M49 code, and country. The dataset also includes estimates in kilograms per capita per year, total tonnes of waste generated per year, and a measure of confidence in each estimate.

### Possible Issues with the Data

1. **Missing Values:**
   - I identified missing values in the dataset and addressed them by replacing them with normalized values.
2. **Data Consistency:**
   - Ensured consistency in data types and formats to prevent issues during analysis. Renamed columns for better clarity and added additional columns for convenience in calculations.
3. **Outliers:**
   - Explored and addressed outliers or anomalies in the dataset to mitigate their potential impact on the analysis results.



### Significance of the Dataset for Research

This dataset is invaluable for researching global patterns of household waste generation. By examining estimates at the regional and country levels, researchers can gain insights into variations, trends, and the reliability of the estimates. It is a crucial resource for studies aiming to understand and address environmental challenges associated with household waste.

## How to Use This Datasets

### Data Files:

- **household_waste_estimates.csv:** The dataset file containing estimates of household waste per country.

### Data Fields:

- **Region:** The geographic region of the country.
- **M49 code:** The M49 code associated with each country.
- **Country:** The name of the country.
- **Household estimate (kg/capita/year):** Estimated household waste per capita per year in kilograms.
- **Household estimate (tonnes/year):** Total estimated household waste generated per year in tonnes.
- **Confidence in estimate:** A measure of confidence associated with each estimate.

### Analysis Steps:

1. Load the dataset into your preferred analysis environment.
2. Address missing values, ensure data consistency, and handle outliers during data cleaning.
3. Conduct exploratory data analysis (EDA) to understand the distribution of household waste estimates.
4. Explore comparative analysis between countries, considering regional variations.
5. Utilize geospatial analysis if geographical information is available.

### Acknowledgments:

Provide proper attribution to the UNEP Food Waste Index Report as the source of the dataset.
