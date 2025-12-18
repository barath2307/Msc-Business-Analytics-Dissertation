# Data-Driven Analysis of ICT and AI-Enabled Analytics Adoption Across Firm Size, Economic Activity, and Time

## Overview
This repository contains the data, code, and analytical outputs supporting an MSc Business Analytics dissertation. The study uses official OECD business statistics to examine patterns of ICT and AI-enabled analytics adoption across firm sizes, economic activities, countries, and time.

The analysis focuses on data-driven decision-making practices, operationalized as organizational adoption of analytics and AI-enabled digital technologies. The study does not assess decision quality or managerial cognition.

## Dataset
- Source: OECD ICT Access and Usage by Businesses
- Type: Secondary, publicly available data
- Key dimensions:
  - Country (REF_AREA)
  - Year (TIME_PERIOD)
  - Economic activity (ACTIVITY)
  - Firm size (SIZE_CLASS)
  - ICT / analytics adoption indicators (MEASURE)

The raw dataset is stored in `Msc Business Analytics Dissertation/data`.

## Repository Structure
- `data/` – Raw and processed datasets
- `notebooks/` – Jupyter notebooks implementing the full analysis pipeline
- `outputs/figures/` – Visualizations used in the dissertation and appendix
- `outputs/tables/` – Summary statistics and analytical tables
- `outputs/regression/` – Regression outputs and robustness checks

## Analytical Methods
The study employs:
- Data cleaning and quality assessment
- Descriptive and comparative analysis
- Time-series trend analysis
- Growth and volatility analysis
- Cross-country comparisons
- ANOVA and post-hoc testing
- Multiple linear regression (associative)
- Interaction effects (firm size × AI-enabled technologies)
- Robustness and diagnostic checks


## Key Contribution
The repository demonstrates how firm size moderates the association between AI-enabled digital technologies and data analytics adoption, highlighting differences in firms’ capacity to translate digital technologies into data-driven decision-making practices.

## Reproducibility
All results can be reproduced by running the notebooks sequentially in the `notebooks/` directory.

## Requirements
pandas
numpy
matplotlib
scipy
statsmodels

## Author
Barathsanjay Velmurugan
University of Greenwich 
Dissertation project
