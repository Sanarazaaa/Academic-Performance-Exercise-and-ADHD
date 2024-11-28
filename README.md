# Exercise and Academic Performance in ADHD

## Motivation

The prevalence of Attention Deficit Hyperactivity Disorder (ADHD) among adolescents and emerging adults is on the rise. Academic performance is a critical component of self-esteem and future opportunities, and understanding the factors that influence it is essential for educators, parents, and healthcare providers.

Physical exercise has been shown to offer numerous benefits for mental health and cognitive function. This project seeks to explore the relationship between physical activity and academic performance in students with ADHD, aiming to uncover insights that could lead to targeted interventions. If a positive correlation is established, it could encourage the integration of physical activity into educational settings as a means to enhance learning outcomes.

## Overview
The **Exercise and Academic Performance in ADHD** project investigates the relationship between physical exercise and academic performance among adolescents and emerging adults diagnosed with Attention Deficit Hyperactivity Disorder (ADHD). The study aims to analyze how various physical activity metrics correlate with academic outcomes, specifically GPA, to provide insights that may inform interventions and support strategies for this population.

## Features
- **Data Analysis**: Analyze the impact of physical activity on academic performance using statistical methods.
- **Visualizations**: Generate informative visualizations to illustrate the relationships between exercise and GPA.
- **Descriptive Statistics**: Summarize key metrics related to physical activity and academic performance.
- **Statistical Testing**: Perform correlation analysis, t-tests, and regression analysis to assess the significance of findings.

## Dataset
The dataset used in this project contains the following columns:
- **Key**: Unique identifier for each entry
- **Steps**: Number of steps taken
- **Peak**: Time spent in peak heart rate zone (minutes)
- **Cardio**: Time spent in cardio heart rate zone (minutes)
- **FatBurn**: Time spent in fat-burning heart rate zone (minutes)
- **Mode**: Type of exercise (e.g., running, cycling)
- **Minutes**: Total minutes of exercise
- **Gender**: Gender of the participant
- **Age**: Age of the participant
- **GPA**: Grade Point Average (academic performance)
- **Life Score**: A subjective score of life satisfaction or well-being

## Installation
To set up the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/exercise-academic-performance.git
   cd exercise-academic-performance
   ```

2. **Install Required Libraries**:
   Ensure you have Python installed, then install the necessary libraries using pip:
   ```bash
   pip install pandas seaborn matplotlib scipy statsmodels
   ```

## Data Analysis
The analysis includes:
- **Descriptive Statistics**: Summary of physical activity metrics and GPA.
- **Visualizations**: Scatter plots and correlation heatmaps to illustrate relationships.
- **Statistical Tests**: T-tests and regression analysis to assess the significance of findings.

## Results
- The analysis indicates that the number of steps taken is positively associated with GPA, suggesting that higher physical activity levels may correlate with better academic performance.
- The overall model explains a relatively small portion of the variance in GPA (R-squared: 0.176), indicating that other factors not included in the model may also play significant roles in academic performance.
- The t-test results show a statistically significant difference in GPA between high and low exercise groups, with a p-value of 0.0025.

## Acknowledgments

- This project is inspired by the principles of health psychology and the study of ADHD.
