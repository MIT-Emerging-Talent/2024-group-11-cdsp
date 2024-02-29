# Zero Waste Initiative

### Milestones timeframe

![alt text](./extras/image.png)

## Overview

Zero Waste offers a systematic approach to avoiding or reusing waste with the aim of minimizing its disposal into landfills. It's a strategic resource management paradigm that is becoming increasingly relevant in today's world, where the need for sustainable development and efficient resource utilization is evident.

# [Milestone 0: Collaborative Development]()

### **Date: 8-19 January, 2024**

## Core Issues

- **Technological Innovations:** What new technologies can be utilized for waste collection, sorting, and processing to achieve zero waste?
- **Educational Programs:** How can public awareness regarding the importance of Zero Waste programs be raised and encourage the adoption of new eco-friendly habits?
- **Waste Management in Cities:** What urban management strategies can facilitate the successful implementation of Zero Waste programs in large cities?

## Generating Ideas and Making Progress

Brainstorm new and creative solutions to reduce waste and promote zero waste initiatives. Test these ideas through simulations or small-scale projects to evaluate effectiveness. Continuously iterate and refine solutions based on feedback from participants and data analysis. Ensure that all solutions are user-friendly, culturally appropriate, and considerate of all stakeholders' perspectives.

## Methodology

- **Understanding People:** Gather insights from personal experiences and data obtained from open sources to analyze stakeholders' perspectives on waste management.
- **Defining the Issue:** Analyze statements from various stakeholder groups to identify key challenges and opportunities in waste management.
- **Generating Ideas and Making Progress:** Engage in collaborative brainstorming sessions to devise innovative solutions. Test these ideas through simulations or small-scale projects, continuously iterating based on feedback and data analysis.

# Project Milestones and Problem Statement

# [Milestone 1: Problem Identification](./milestone/milestone_1)
### **Date: 22-26 January, 2024**

## Milestone Overview:
**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_1/README.md)_**

Explore the problem statement based on our team's personal experiences, categorized by the countries where we reside.

- [Group Member Experience](./milestone/milestone_2/our_experience.md)

### Actionable Research Questions:
Throughout the project, we refined our research questions for greater specificity:

1. What is the average per capita household food waste in the studied region, and how does it vary across different income brackets or urban and rural areas?
2. What is the collective economic impact of food waste on a global scale, and how does it affect different regions economically?
3. Are there correlations between the economic prosperity of a region and its success in implementing effective food waste reduction initiatives?

## Milestone Retrospective
- [Retrospective 1](./retrospective/retrospective_1.md)

## 🌱 Problem Identification, Domain Understanding, and Statement
Our project addresses challenges in implementing Zero Waste programs, with a particular focus on cultural and geographical factors hindering the adoption of new consumption practices and waste management strategies within the food industry.

### Region Overview
Our team works with global data and analysis, with a focus on countries where team members currently reside.


# [Milestone 2: Data Collection](./milestone/milestone_2)

### **Date: 29 January - 2 February, 2024**

## Milestone overview:
**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_2/README.md)_**

## Non-Technical Explanation of Domain Modeling

Domain modeling in our Zero Waste project involves creating a simplified representation of key aspects related to waste management. It's a visual guide, akin to a map, helping us understand how economic indicators, cultural differences, and geography influence waste generation and management practices.

This non-technical model serves as a blueprint, aiding communication, identifying challenges, and guiding decision-making for effective waste reduction strategies.

## Data Set Documentation

We utilize datasets from USDA, FeedAmerica, and UN organizations, providing a comprehensive view of related problems.

Link to Data Set(includes sources): [**Data Set**](https://1drv.ms/x/s!AgDpCOgvTPWroG6YVK6Ut_Wk3KeY?e=ghfJ5p)

1. [**Household food Waste by country**](./milestone/milestone_3/analysis_waste/household_waste.csv)
2. [**Service food Waste by country**](./milestone/milestone_3/analysis_waste/food_service_waste.csv)
3. [**Retail food Waste by country**](./milestone/milestone_3/analysis_waste/retail_food_waste.csv)

## Data Collection and Cleaning Scripts

For transparency and replication, we provide all scripts for data collection and cleaning, covering the entire process, including data partitioning.

## Our Research Work

Engaged in Data Science research, our team focuses on implementing zero waste programs, leveraging practical experience and modern data analysis methods to contribute significantly to the field.

For more details on our experience, refer to [**our_experience**](./milestone/milestone_2/our_experience.md) and [**README**](./milestone/milestone_2/README.md).

## Milestone retrospective

- [Retrospective 2](./retrospective/retrospective_2.md)

# [Milestone 3: Data Analysis](./milestone/milestone_3)

### **Date: 5-16 February, 2024**

## Milestone overview:
**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_3/README.md)_**

![alt text](/extras/1-1-1180x617.png)
The project analyzes the relationship between economic indicators and waste generation using data from the [2021 UNEP Food Waste Index Report](</extras/FWD%20(1).xlsx>).

## `Non-technical explanation of our findings`

Our exploration of the relationship between economic indicators and global waste generation patterns yielded several insights. The dataset, covering diverse countries, allowed us to observe trends and variations in economic factors and waste production.

## Key Findings:

The overall model does not explain a significant proportion of the variance in the total waste estimate (R-squared = 0.156). Additionally, individual economic indicators do not exhibit strong statistical significance in predicting the total waste production.

1. **Working Hours and Wages:**
   - Standard working week averages around 38.2 hours.
   - Monthly minimum wages vary from 170 to 3298.4 USD.

2. **Financial Indicators:**
   - Lending rates average at 6.03%.
   - GDP per capita averages at 57.90 thousand USD.

3. **Human Development Index (HDI):**
   - Average HDI is 0.894.

![alt text](./extras/HDI.png)

4. **Waste Production:**
   - Total waste production ranges from 38.8 thousand tonnes to 45.4 million tonnes.

![alt text](./extras/waste_production_sector.png)

## `Levels of Certainty`

While expressing moderate to high confidence in our findings, it's crucial to acknowledge potential uncertainties associated with data limitations, assumptions, and sampling variability.

## `Technical description of analysis`

Results of the data analysis conducted using Jupyter Notebook can be found [**here**](/milestone/milestone_3/total_analysis.ipynb).

## `Technical explanation of our findings`

### Key Findings and Insights

1. **Household Food Waste Across Regions:**
   - Poland and the USA exhibit similar per capita household food waste.
   - Canada and Denmark show higher estimates, indicating advanced waste management systems.

2. **Global Economic Impact of Food Waste:**
   - Global average food waste volume is around 3.17 million tonnes.
   - Higher development level countries like the USA have larger volumes of food waste.

3. **Relationship Between Economic Prosperity and Food Waste Reduction Initiatives:**
   - Sensitivity to economic indicators suggests regions with higher economic development may have more resources for waste reduction initiatives.
   - Supplementary research is recommended for a comprehensive understanding.

## `Possible Alternative Approaches`

1. **Machine Learning Models:**
   - Explore models like Random Forest or Gradient Boosting for predictive modeling.

2. **Robust Regression:**
   - Consider robust regression techniques like Huber regression to address potential outliers.

3. **Advanced Geospatial Techniques:**
   - Utilize advanced geospatial analysis techniques for deeper insights into regional waste distribution patterns.

### Applying the Results:

The findings can be used for further research and development of waste management strategies in the context of economic development.

---

_For a detailed analysis, refer to the [Full Project Analysis](./milestone/milestone_3/README.md) in the project repository._

## Milestone retrospective

- [Retrospective 3](/retrospective/retrospective_3.md)

## Scripts and documentation

### Scripts

- [**analysis_waste**](./milestone/milestone_3/analysis_waste): Detailed waste analysis, including data type checking, processing, cleaning, and statistical analysis.

- [**Summary analysis**](./milestone/milestone_3/total_analysis.ipynb): Estimates of household, food service, and retail waste per country from the 2021 UNEP Food Waste Index Report.

- [**Predictions**](./milestone/milestone_3/prediction/): Analysis addressing data gaps, sensitivity scenarios, and risk sources.

### Documentation

- [**Analysis_Waste**](./milestone/milestone_3/analysis_waste/README.md)

- [**Analysis**](./milestone_3/README.md)

- [**Machine Learning Prediction**](./milestone/milestone_3/prediction)

- [**Prediction Analysis**](./milestone/milestone_3/prediction/analysis_code.md)

- [**Prediction documentation**](./milestone/milestone_3/prediction/README.md)



## `Conclusion:`

Adapting methods based on ongoing discoveries ensures a dynamic and thorough analysis approach. [Answers](./milestone/milestone_3/research_questions.md) for [Actionable Research Questions](./milestone/milestone_1/research_question.md).



**_Please be aware that the analysis is currently underway, and any updates or improvements will be incorporated into future milestones._**



# [Milestone 4: Communicating Results](./milestone/milestone_4)

### **Date: 19 February - 2 March, 2024**

## Milestone overview:

**_Be aware that the full description of this milestone you can find by refer to [README](./milestone/milestone_4/README.md)_**

## Selecting the Target Audience:

Our focus is on Nonprofit Organizations dedicated to addressing social and environmental issues, specifically in the realm of food waste. We aim to engage organizations with significant influence on groups contributing to food waste, such as households, food service, and retail.

## Key Strategies for Nonprofit Organizations to Reduce Food Waste:

- **Promoting Conscious Consumption:**
  - Conduct information campaigns and educational activities for consumers on healthy eating and responsible food handling.

- **Supporting Restaurants and Catering Establishments:**
  - Advocate for programs encouraging storage and use of leftovers in restaurants and food service establishments.

- **Developing Food Recycling Programs:**
  - Promote initiatives for food recycling in food service locations, encouraging waste sorting and recycling.

- **Establishing Partnerships with Grocery Stores:**
  - Collaborate with grocery stores and food providers to minimize food rejection and wastage.


## Limitations:

- **Financial Limitations:**
  - Nonprofit organizations may have limited financial resources.

- **Resource Constraints:**
  - Some organizations may face resource limitations.

- **Partnership Opportunities:**
  - Identifying new opportunities for collaboration and development.

## Cooperation Strategies:

- **Direct Appeal:**
  - Approach nonprofit organizations directly, offering cooperation and resource sharing.

- **Partnerships:**
  - Establish partnerships with organizations, sharing knowledge, resources, and expertise.

- **Organizing Events:**
  - Hold joint events, workshops, and trainings to raise awareness and foster collaboration in reducing food waste.



## Milestone retrospective

- [Retrospective 4](./retrospective/retrospective_4.md)

# Milestone 5: Final Presentation Event

### **Date: 5-9 January, 2024**

1. A 1-minute pitch for your solution.
2. A 3-minute presentation of your
   group’s process from beginning to end
   including challenges you faced,
   lessons you learned, and any advice
   you have for future learners.
3. A retrospective for this milestone.

# Contributing

We welcome contributions from individuals and organizations passionate about waste management and sustainability. To contribute, please follow these guidelines:

- Fork the repository and create a new branch for your contributions.
- Make your changes, ensuring they adhere to project guidelines and standards.
- Submit a pull request detailing the changes you've made and why they're beneficial.

Thank you for helping us make a positive impact on waste management!
