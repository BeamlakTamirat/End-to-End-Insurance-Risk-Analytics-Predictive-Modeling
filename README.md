# Insurance Risk Analytics and Predictive Modeling

A data science project for analyzing insurance risk data and building predictive models.

## Overview

This project performs comprehensive analysis on insurance policy data to identify risk factors and patterns. It includes data cleaning, exploratory data analysis (EDA), and statistical testing.

## Project Structure

```
├── notebooks/          # Jupyter notebooks for analysis
│   ├── data-cleaning.ipynb
│   ├── univariate-analysis.ipynb
│   ├── multivariate-analysis.ipynb
│   └── ab-testing.ipynb
├── scripts/            # Python modules for data processing
│   ├── eda.py          # Exploratory data analysis functions
│   ├── preprocess.py   # Data preprocessing utilities
│   └── convert-data.py
└── data/               # Data files (managed by DVC)
```

## Features

- **Data Cleaning**: Handles missing values, data type conversions, and data quality issues
- **Univariate Analysis**: Statistical analysis of individual variables
- **Multivariate Analysis**: Correlation and relationship analysis between variables
- **A/B Testing**: Statistical hypothesis testing for insurance policies

## Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run data cleaning notebook to prepare the dataset
2. Perform univariate and multivariate analysis
3. Execute A/B testing for policy comparisons

## Data

The project uses `MachineLearningRating_v3` dataset, managed with DVC for version control.
