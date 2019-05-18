# Insurance Forecast

## Problem Statement
The purpose of this analysis is to predict individual health insurance costs charged by health insurance companies based on age, sex, BMI, children, smoking, and region.

## Team Members
* Jason Zelaya
* Madeleine Merken
* Shannon Chang

## Data Source
Kaggle: https://www.kaggle.com/mirichoi0218/insurance

## Data Content
* Age: Age of the beneficiary in years.
* Sex: Whether the beneficiary is male or female.
* BMI: Body mass index derived from the weight and height of an individual. A healthy BMI is generally known to be from 18.5 to 24.9.
* Children: Number of dependents covered by health insurance.
* Smoker: Whether or not the beneficiary smokes.
* Region: The beneficiary's residential area in the US. The categories are northeast, southeast, southwest, northwest.
* Charges: The price the beneficiary pays the health insurance companies in USD.

**Note: The individual paying for the health insurance is referred to as the "beneficiary" in the definitions.

## Underlying Assumptions
The model should conform to the assumptions of linear regression to be usable in practice. To confirm this we  will examine the data set to check:
* The regression model is linear in parameters
* The mean of residuals is zero
* Homoscedasticity of residuals or equal variance
* Normality of residuals

## ML Algorithm
* Multi-linear regression (supervised learning)
* pd.crosstab categorical variable sex smoker region to confirm values
* check for typo
* dollars, round decimals
* range of age
* incorrect entries
* data validation = exploratory data analysis
* data validation = cleaning the data
