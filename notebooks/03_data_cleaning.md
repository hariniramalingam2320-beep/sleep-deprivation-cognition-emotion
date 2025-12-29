# Data Cleaning and Preprocessing

This document outlines the data cleaning and preprocessing steps applied prior to analysis to ensure data quality, consistency, and interpretability.

## Handling Missing Values

The dataset will be examined for missing values in key variables, including:
- Sleep duration and sleep quality
- Cognitive task performance measures
- Emotional stability scores

If missing values are present, appropriate strategies such as removal or simple imputation will be applied depending on the extent and nature of missingness.

## Data Validity Checks

The following validity checks will be performed:
- Removal of impossible or invalid values (e.g., negative reaction times)
- Verification of plausible score ranges for cognitive task measures
- Consistency checks across related variables

## Variable Preparation

Prior to analysis:
- Reaction time measures may be standardized to allow comparison across tasks
- Categorical variables (e.g., gender, physical activity level) will be encoded as needed
- Summary or composite measures may be computed for cognitive task performance

## Output

The cleaned dataset will be saved as a processed file and used for all subsequent analyses in this project.
