# A/B Test Analysis

## Objective
To determine if a new marketing campaign had an impact on conversion rates compared to the existing campaign.

## Data
There are two data sets in this project, Control Group and Test Group, which contain information about the campaigns.

## Methodology
1. Import and clean the data for the control and test groups.
2. Determine the conversion rates for both groups.
3. Perform a Z-test to determine if the difference in conversion rates is statistically significant.

### Thank you Kaggle.com for providing the dataset, which can be found here https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset?resource=download

### Necessary Libraries
python, pandas as pd, from statsmodels.stats.proportion import proportions_ztest, numpy as np
