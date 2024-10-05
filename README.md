# StrokeData-Eda-Visualization
# Project Overview
This project represents an Exploratory Data Analysis (EDA) and visualization of a dataset related to stroke prediction. The goal was to analyze various health-related factors such as BMI, glucose levels, and lifestyle habits, which can potentially contribute to strokes. This analysis was part of my final exam project for the "Introduction to Data Science" course during my first semester.

# Purpose of the Project
The main objective of this project was to explore the dataset thoroughly and perform statistical analyses to understand how different factors are correlated with the occurrence of stroke. The analysis involved both univariate and multivariate approaches, focusing on key health indicators that might predict stroke risks.

# Objectives
- Perform data cleaning, including identifying missing values and dealing with outliers.
- Conduct EDA to identify distributions, relationships, and patterns within the dataset.
- Visualize key metrics, such as BMI, average glucose levels, and stroke incidences, to draw insights.
- Summarize findings and interpret visualizations to provide insights into stroke risk factors.

# Methods
1. Data Cleaning and Preprocessing:
  - Checked for missing values in critical columns like bmi and avg_glucose_level.
  - Filled missing values where appropriate or dropped records that could potentially lead to incorrect analysis.
  - Identified and treated outliers in columns like bmi to ensure the dataset is suitable for analysis.

2. Exploratory Data Analysis (EDA):
  - Univariate analysis was performed on different attributes to understand their individual distributions (e.g., BMI, age).
  - Bivariate analysis focused on relationships between categorical variables like smoking status and stroke occurrence.
  - Multivariate analysis using plots to explore complex relationships, such as age and hypertension impact on stroke, visualized with respect to gender.

3. Data Visualization:
  - Seaborn and Matplotlib were used to create informative visualizations.
  - Box plots for BMI helped detect outliers.
  - Count plots and factor plots were employed to understand categorical relationships (e.g., smoking status vs. stroke).

# Tools Used
- Programming Language: Python
- Libraries: Pandas (for data manipulation), Matplotlib & Seaborn (for data visualization), NumPy (for numerical operations).

# Key Insights
- BMI Outliers: There were several individuals with very high BMI (above 45) indicating potential health risks.
- Imbalanced Data: The majority of data points represented individuals without stroke, which indicates an imbalanced dataset. This is crucial to consider for future modeling efforts.
- Risk Factors: Smoking status, age, BMI, and glucose levels all had observable impacts on stroke occurrences, highlighting areas for further exploration or health interventions.

# Challenges and Solutions
- Imbalanced Data: The dataset was highly imbalanced with most individuals not having experienced a stroke. Special attention is needed when building predictive models to handle this imbalance.
- Outliers in BMI: Outliers were detected and removed where necessary to avoid skewed analyses.

# Conclusion
This project provided an understanding of how different health and lifestyle factors correlate with stroke risks. It helped me build foundational skills in data cleaning, exploration, visualization, and correlation analysis. The insights derived from this analysis could serve as a preliminary step towards building predictive models for stroke occurrence, especially focusing on identified risk factors like smoking status and BMI.
