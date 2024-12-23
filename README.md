# Case Study: Impact of Lifestyle and Demographic Factors on Sleep Duration

## Overview

This project explores the relationship between lifestyle, demographic factors, and sleep duration using Bayesian linear regression. Through this analysis, I aim to uncover trends and significant predictors of sleep patterns, focusing on the role of physical activity, screen time, and dietary habits.

## Objectives

- Analyze how demographic and lifestyle factors influence sleep duration.
- Identify patterns among different groups based on age, gender, and habits.
- Quantify the effects of screen time, sports, and meals on sleep duration.

## Data Description

The data was collected using a Google Form distributed among friends and family. It includes:

- **Gender**: Male, Female, or Prefer Not To Answer.
- **Age**: Continuous variable representing the respondent's age.
- **Daily_meals**: Number of meals per day (categorical).
- **Hours_sport_per_week**: Time spent on physical activities per week (continuous).
- **Hours_sleep_per_day**: Average sleep duration per day (continuous).
- **Hours_screen_per_day**: Time spent on screens daily (continuous).

The dataset consists of 128 observations and 7 variables.

## Methodology

1. **Preprocessing**:
   - Cleaned and transformed categorical variables into factors.
   - Categorized age into two groups: Young Adults and Adults, based on bimodal distribution.
   - Removed irrelevant observations for better model accuracy.

2. **Exploratory Data Analysis**:
   - Visualized distributions with histograms and pie charts.
   - Examined relationships and trends among variables.

3. **Bayesian Linear Regression**:
   - Used MCMC sampling to model predictors of sleep duration.
   - Analyzed the statistical significance and credible intervals of predictors.

## Key Findings

- **Gender**: Males sleep slightly more than females.
- **Age**: Young adults sleep more than older adults.
- **Lifestyle**: Physical activity is positively correlated with sleep duration, while screen time has a negative impact.
- **Diet**: Consuming more meals per day shows a trend towards longer sleep duration.

