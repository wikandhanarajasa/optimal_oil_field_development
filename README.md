# Prospecting for 200 New Oil Wells for Oil Company

## Introduction

This project is part of a strategic initiative at OilyGiant (a fictional company) aimed at identifying and developing 200 new profitable oil wells. The primary objective is to leverage data analysis and predictive modeling techniques to find the most lucrative locations for oil extraction. The results will guide decision-making on which areas offer the best financial returns and the lowest risks.

## Goal

The project's goals are:

- **Profit Estimation**: Determine the average profit for each potential well and establish a 95% confidence interval for these estimates.
- **Risk Assessment**: Evaluate the potential loss percentage to understand the risk associated with each well.
- **Area Selection**: Identify the most suitable geographic area for oil extraction based on projected profits and risk assessments.

## Stages

### 1. Data Preparation and Exploration

- Load and examine the data provided.
- Conduct exploratory data analysis to understand the general characteristics and distribution of the data.

### 2. Model Development and Training

- Develop a machine learning model to predict oil reserves in new wells.
- Train the model using the provided data and validate its performance.

### 3. Model Evaluation

- Implement bootstrapping techniques to estimate profitability and assess risk.
- Calculate key metrics such as average predicted reserves, confidence intervals, and potential losses.

### 4. Area Selection

- Use the model's predictions to identify the top-performing wells.
- Select the geographic areas with the highest total projected profits.

### 5. Conclusion Drawing

- Summarize findings and make recommendations on the most profitable areas for oil well development.
- Ensure the selected areas meet the criteria of having less than a 2.5% risk of loss.

## Data Content

The provided datasets include:

- **Non-Categorical Data:**
  - `id`: Unique identifier for each oil well.

- **Features:**
  - `f0`, `f1`, `f2`: Various features related to the oil wells.

- **Target:**
  - `product`: Oil reserve volume (1 unit = 1,000 barrels).

## Project Description

### Data Analysis

- Review parameters from existing wells, including oil quality and reserve volumes.
- Train and validate a predictive model for oil reserves based on historical data from three distinct regions.
- Calculate and compare the projected average revenue from oil wells in each region.

### Model Training

- **Model Used**: Linear Regression
- **Data Split**: 75% training, 25% validation
- **Evaluation Metrics**: RMSE, MAPE

### Profitability Analysis

- Calculate and compare the projected average revenue from oil wells in each region.
- Ensure the investment aligns with a minimum average return of $500,000 per well to avoid losses.

### Risk and Profit Calculation

- Implement bootstrapping to estimate profit distributions and assess risk.
- Select regions with the highest average profit and lowest risk.

### Recommendation

- Provide a well-reasoned recommendation for the best region to develop new oil wells, supported by the analysis.

## Project Constraints

- Use linear regression for model training.
- The budget for developing 200 wells is USD 100 million.
- Revenue from one barrel of crude oil is USD 4.50, making each unit of the product worth USD 4,500.
- Consider only regions with less than a 2.5% risk of loss for the final recommendation.

**Note**: The data provided is simulated and does not include real contract details or specific well characteristics.

## Conclusion

Based on the analysis:

- **Data Analysis**: All datasets show no signs of duplicate values, improper data types, or missing values. Feature `f2` shows a high correlation with `product`, especially in `data1`.
- **Model Performance**: Data1 exhibited the lowest RMSE and MAPE, indicating the best model accuracy.
- **Profit Calculation**: Region 0 has the highest potential profit, but Region 1 shows the lowest risk of loss.

**Final Recommendation**: Region 1 is the most suitable for new oil well development due to its highest average profit and lowest risk of loss.

