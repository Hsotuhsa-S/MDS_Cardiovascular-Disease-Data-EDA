# Cardiovascular Disease Data Analysis

## Overview
This project is part of the Data Science coursework at Heidelberg University, focusing on statistical analysis of cardiovascular disease data using R. The analysis focuses on examining relationships between various risk factors and cardiovascular disease occurrence.

## Motivation

The data science methods used include data cleaning, handling implausible values, statistical correlation analysis, visualization, and hypothesis testing, which are fundamental in data science practice.
The data science methods used include data cleaning, handling implausible values, Feature Engineering, statistical correlation analysis, visualization, and hypothesis testing, which are fundamental in data science practice.
The analysis includes:
- Data preprocessing and cleaning
- Feature engineering (BMI calculation)
- Statistical correlation analysis
- Distribution analysis
- Risk factor assessment

## Key Features

### Data Preprocessing
- Handling implausible values
- Removing duplicates
- Converting categorical variables
- Scale transformations
- Missing value analysis

### Feature Engineering
- BMI (Body Mass Index) calculation using:
  ```r
  BMI = weight(kg) / [height(m)]^2
  ```

### Statistical Analysis
- Correlation analysis between:
  - Systolic blood pressure and BMI
  - Diastolic blood pressure and BMI
- Distribution analysis of age across different categories
- Chi-squared tests for risk factors

### Visualization
- Box plots for age distribution
- Scatter plots for blood pressure vs BMI
- Density plots for age distribution
- Histograms with stacked bars

## Tools & Technologies
- R for statistical computing
- Libraries:
  - tidyverse: Data manipulation and visualization
  - ggplot2: Data visualization
  - patchwork: Combining multiple plots
  - kableExtra: Enhanced table formatting

## Code Structure
- `Cardio_HomeWork_2022.qmd`: Main analysis file
- `data/`: Directory containing datasets
  - `cardio_train.csv`: Raw data
  - `tidyCardioData.RData`: Preprocessed data
  - `cardioDataTask2.RData`: Data with engineered features

## Course Context
This work was completed as part of the Data Science course curriculum at Heidelberg University, 2022.
