# Regression_Analysis_for_Startup_Profit_Prediction
Tools used -  (1) Microsoft Excel   (2) Power Bi

## Overview
This project focuses on analyzing the impact of spending on Research & Development, Administration, and Marketing on the profits of startups. The analysis utilizes regression analysis to establish a relationship between these variables and predict the profit of startups based on their spending.

## Dataset
The dataset used in this project contains information from 50 startups located in New York, California, and Florida. It includes the following attributes:
- R&D spending
- Administration spending
- Marketing spending
- State
- Profit

## Methodology
1. **Regression Analysis**: Linear regression was performed to model the relationship between the independent variables (R&D spending, Administration spending, Marketing spending) and the dependent variable (Profit).

## Solution
### Regression Analysis Results
- **Equation**: Profit = 0.8057(R&D_Spend) - 0.0268(Administration_Spend) + 0.0272(Marketing_Spend) + 50122.19
- **R-squared value**: 0.95 (indicating 95% accuracy of the model)

### Profit Prediction
1. If R&D_Spend is $21,892.92, Administration_Spend is $81,910.77, and Marketing_Spend is $164,270.7, the predicted profit is $70,037.90477.
2. If R&D_Spend is $23,940.93, Administration_Spend is $96,489.63, and Marketing_Spend is $137,001.1, the predicted profit is $70,554.57256.

## Insights
- The model suggests that spending more on Research & Development tends to yield higher profits for startups.
- Conversely, higher spending on Administration may not significantly impact profits.
- Marketing spending, while still contributing to profit, has a relatively smaller effect compared to R&D spending.

