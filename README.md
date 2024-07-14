# Predicting Car Insurance Claims

## Overview

Insurance companies invest significant resources into accurately predicting customer behavior, such as the likelihood of filing insurance claims. On the Road car insurance approached us to build a predictive model that determines whether a customer will make a claim during their policy period. This project aims to identify the most predictive feature using machine learning techniques, specifically logistic regression, to assist On the Road in optimizing their pricing and risk assessment strategies.

## Dataset

The dataset, `car_insurance.csv`, contains various client attributes and a binary outcome indicating whether a claim was made:

- `id`: Unique client identifier
- `age`: Client's age category
- `gender`: Client's gender
- `driving_experience`: Years the client has been driving
- `education`: Client's level of education
- `income`: Client's income level
- `credit_score`: Client's credit score (normalized)
- `vehicle_ownership`: Client's vehicle ownership status
- `vehicle_year`: Year of vehicle registration
- `married`: Client's marital status
- `children`: Number of children
- `postal_code`: Client's postal code
- `annual_mileage`: Number of miles driven annually
- `vehicle_type`: Type of vehicle
- `speeding_violations`: Total number of speeding violations
- `duis`: Number of times caught driving under the influence
- `past_accidents`: Total number of previous accidents
- `outcome`: Binary variable indicating if a claim was made (0: No claim, 1: Made a claim)

## Methodology

1. **Data Preparation**: Handle missing values for `credit_score` and `annual_mileage`.
2. **Model Building**: Build logistic regression models for each feature to predict the `outcome`.
3. **Model Evaluation**: Calculate accuracy metrics to determine the best performing feature.

## Implementation

### Requirements

Ensure you have Python and the following libraries installed:

- pandas
- numpy
- statsmodels

### Steps to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/NonsoOmoko/Project-Modelling-Car-Insurance-Claim-Outcomes.git
   cd Project-Modelling-Car-Insurance-Claim-Outcomes
