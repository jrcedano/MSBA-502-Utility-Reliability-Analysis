# MSBA-502-Utility-Reliability-Analysis
Analysis of underground power infrastructure and electricity outage reliability across U.S. utilities (2021–2025)

## Project Title
Burying the Lines: Underground Power and Outage Reliability

## Team Members
Andrew Massa
Jeremiah Cedano

## Project Overview
This project examines the relationship between underground
electrical infrastructure and power outage reliability
among U.S. investor-owned utilities from 2021 to 2025.

## Research Question
Do utilities with higher underground infrastructure
shares experience fewer power outage minutes?

## Data Sources
- Energy Information Administration (EIA Form 861)
- Federal Energy Regulatory Commission (FERC Form 1)
- PUDL crosswalk for matching utility identifiers

## Dataset
- 577 observations
- 89 utilities
- 2021–2025

## Methodology
We used Python to clean, merge, and analyze utility data.

Statistical methods included:
- Descriptive statistics
- Correlation analysis
- Simple linear regression
- Multiple linear regression
- Regression with major event days included

## Key Findings
1. Underground infrastructure was significantly
   associated with fewer outage minutes.

2. A 10-percentage-point increase in underground
   infrastructure share was associated with approximately
   22 fewer outage minutes per customer annually,
   controlling for the other model variables.

3. When major weather events were included,
   the estimated relationship increased to
   approximately 88 fewer minutes.

4. The multiple regression model explained
   approximately 28% of the variation in outage duration.

## Business Recommendations
Utilities with low underground infrastructure shares
and poor reliability should evaluate targeted
underground infrastructure investments.

Future research should examine installation costs,
cost-effectiveness, and long-term financial benefits.

## Tools Used
- Python
- pandas
- NumPy
- statsmodels
- Matplotlib
- Jupyter Notebook

## Limitations
Results demonstrate statistical associations,
not proven causal effects.
