# Total Waste Prediction and Reduction Analysis

This Jupyter Notebook contains Python code for predicting total waste generation in Canada from 2016 to 2024 using linear regression. Additionally, it includes a prediction for 2024 with waste reduction based on research indicating an estimated reduction of 2.15-2.35% in waste generation.

## Code Overview

### Dependencies

- pandas
- scikit-learn
- matplotlib
- seaborn
- random

### Code Structure

1. **Data Preparation:**

   - Generates variations for existing data points.
   - Creates an initial dataset (`df_original`) and calculates the 'total_waste' column.

2. **Model Training:**

   - Splits the data into training and testing sets.
   - Builds a linear regression model and evaluates its performance using mean squared error.

3. **Visualization:**

   - Plots actual vs predicted total waste over the years.

4. **Data Update:**

   - Adds new data points for 2016, 2017, 2022, and 2023 with variations.
   - Calculates the 'total_waste' for the updated dataset (`df_updated`).

5. **Prediction for 2024:**

   - Makes predictions for the next year (2024) with and without waste reduction.

6. **Visualization of Updated Dataset:**
   - Plots the total waste from 2016 to 2023 with predictions for 2024.

## Usage

To run the code, make sure to have the required dependencies installed. You can use the following commands:

```bash
pip install pandas scikit-learn matplotlib seaborn
```

# Additional Note

The prediction for 2024 with waste reduction (future_prediction_2024_with_reduction) is based on research findings indicating an approximate reduction in waste generation for the types of waste considered in the analysis depending of country.

[Problem-solving Approaches in Code Analysis](https://github.com/MIT-Emerging-Talent/2024-group-11-cdsp/tree/main/milestone/milestone_3/prediction/analysis_code.md) - This file contains code for data analysis and forecasting, along with approaches to addressing identified issues.

Feel free to adjust parameters, conduct further research, or modify the code to suit your specific needs.
