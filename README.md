# Insurance Fraud Detection - A Data Story

## Project Overview

This project analyzes insurance claim fraud patterns using a dataset of 1,000 claims from January to March 2015 across seven US states. The analysis reveals that 24.7% of claims are fraudulent, with fraudulent claims averaging $60,302 - nearly 20% higher than legitimate claims. Through comprehensive data analysis, this project identifies key fraud indicators including temporal patterns, demographic profiles, and behavioral red flags that can enhance fraud detection capabilities.

Data source: Kaggle - [Auto Insurance Claims Data](https://www.kaggle.com/datasets/buntyshah/auto-insurance-claims-data/data)

## Dataset Description

The analysis uses an insurance claims dataset containing:

1. 1,000 insurance claims from Q1 2015
2. 39 features covering customer demographics, policy details, incident characteristics, and claim amounts
3. Geographic coverage across 7 states: SC, VA, NY, OH, WV, NC, PA
4. Fraud labels (Y/N) for supervised analysis

## Project Structure

The project follows a structured data analysis approach:

1. Data Understanding & Hygiene

* Conducted comprehensive data quality assessment identifying 4 fields with missing values
* Addressed missing values through logical imputation (e.g., 'Not Applicable' for collision_type in non-collision incidents)
* Standardized date formats and corrected data entry errors
* Fixed anomalies including negative umbrella limits and pre-policy incident dates

2. Exploratory Data Analysis

Analyzed fraud patterns across multiple dimensions:

* Temporal: Identified peak fraud hours (11 AM - 4 PM) and high-risk days (Mondays 29.4%, Saturdays 28.3%)
* Geographic: Mapped fraud hotspots with Ohio showing 43.5% fraud rate
* Demographic: Profiled high-risk segments (executive-managerial occupation 36.8%, long-tenure customers 29.4%)
* Behavioral: Uncovered red flags (no authorities contacted in only 2.4% of fraud cases)
*  Examined financial impact showing fraudulent claims cost 19.9% more than legitimate ones

3. Pattern Recognition & Risk Profiling

* Identified high-risk vehicle combinations (BMW X6 43.8%, Chevrolet Silverado 40.9%)
* Discovered correlation between customer tenure and fraud probability
* Analyzed incident type patterns (Single Vehicle Collision 29.0% vs Vehicle Theft 8.5%)

4. Data Story Development

Synthesized findings into five critical questions:

* Who commits fraud? (demographic and behavioral profiles)
* When does fraud occur? (temporal patterns)
* Where does fraud happen? (geographic hotspots)
* What types of incidents are fraudulent? (incident characteristics)
* How much does fraud cost? (financial impact analysis)

5. Building the Dashboard

Preview of the dashboard:

1. All Data Preview

![insurance-fraud-detection](https://github.com/m-vila/insurance-fraud-detection/blob/main/Geico%20Dashboard%20prev%20-%20all%20data.png?raw=true)

2. Jan 2015 Data Preview

![insurance-fraud-detection](https://github.com/m-vila/insurance-fraud-detection/blob/main/Geico%20Dashboard%20prev%20-%20Jan%202015.png?raw=true)

3. Feb 2015 Data Preview

![insurance-fraud-detection](https://github.com/m-vila/insurance-fraud-detection/blob/main/Geico%20Dashboard%20prev%20-%20Feb%202015.png?raw=true)

4. Mar 2015 Data Preview

![insurance-fraud-detection](https://github.com/m-vila/insurance-fraud-detection/blob/main/Geico%20Dashboard%20prev%20-%20Mar%202015.png?raw=true)


## Future Work

Potential extensions to this analysis could include:

* Machine learning models for real-time fraud prediction
* Cost-benefit analysis of fraud prevention strategies
* Integration with external data sources (weather, economic indicators)
