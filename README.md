# Cancer Research Data Analysis

This project involves the analysis of cancer research data to gain insights into the effectiveness of different drug regimens in reducing tumor volumes in mice. The analysis includes data cleaning, statistical summaries, visualizations, and linear regression.

## Overview

The project involves analyzing cancer research data to identify trends, patterns, and correlations related to tumor volume reduction in mice under different drug regimens. The analysis includes data cleaning, statistical summaries, visualizations, and linear regression modeling.

## Dataset

The dataset consists of information on 249 unique mice, including records of multiple timepoints and various drug regimens.

## Data Cleaning

Duplicate entries were identified and removed to ensure data integrity. The resulting clean dataset, named `clean_data`, is ready for analysis.

## Drug Regimen Analysis

Four drug regimens - Capomulin, Ramicane, Infubinol, and Ceftamin - were selected for focused analysis. Summary statistics were calculated to understand the characteristics of tumor volumes under each regimen.

## Gender Distribution

Pie charts were generated to visualize the gender distribution among the mice in the dataset, providing insights into the population composition.

## Final Tumor Volume Analysis

The final tumor volumes at the last timepoint for each mouse in selected drug regimens were analyzed. Box plots were used to illustrate the distribution of final tumor volumes, aiding in the identification of potential outliers.

## Linear Regression

A linear regression model was fitted to explore the relationship between mouse weight and average tumor volume for the Capomulin regimen. The correlation coefficient was also calculated.

## Key Findings

- Capomulin and Ramicane showed lower tumor volumes, indicating potential efficacy.
- Infubinol and Ceftamin exhibited higher variability in tumor volumes.
- Gender distribution among mice is balanced.

## Recommendations

- Validate observed differences with statistical tests.
- Collaborate with domain experts for biological insights.
- Explore additional variables for a more comprehensive analysis.

## How to Use

1. Clone the repository.
2. Open the Jupyter Notebook file (`Cancer_Research_Analysis.ipynb`) in a Jupyter environment.
3. Run each cell to reproduce the analysis.
