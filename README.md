# Pymaceuticals Inc. Squamous Cell Carcinoma (SCC) Treatment Analysis

## Overview

This repository contains the analysis of clinical trial data for Pymaceuticals Inc., a pharmaceutical company specializing in anti-cancer drug therapies. The primary focus of this study is the drug Capomulin, used in the treatment of squamous cell carcinoma (SCC), a form of skin cancer.

## Objective

The goal of the analysis is to compare the performance of Capomulin against other treatment regimens by observing and measuring tumor development in 249 mice over 45 days.

## Repository Contents

- Data cleaning and preparation scripts
- Summary statistics of tumor volume across different drug regimens
- Visualizations including bar charts, pie charts, and box plots
- Calculation of quartiles, IQR, and identification of outliers
- Line plots and scatter plots showing the relationship between tumor volume and other variables
- Correlation and regression analyses between mouse weight and tumor volume for the Capomulin treatment
- A detailed technical report of the study results

## Data

The analysis is based on two datasets:

- `mouse_metadata.csv`: Contains information about the mice.
- `study_results.csv`: Contains the results from the study.

These datasets have been merged and cleaned for the analysis.

## Methods

Various Python libraries such as Pandas, Matplotlib, and SciPy have been utilized for data manipulation and visualization. Specific methods include:

- Aggregation and group-by techniques for summary statistics
- Pandas and Matplotlib for generating plots
- Outlier detection using IQR
- Linear regression and correlation calculation using SciPy

## Results

The results indicate a strong correlation between mouse weight and average tumor volume for the Capomulin regimen, with a correlation coefficient of 0.84.

## Usage

To replicate the analysis:

1. Clone the repository.
2. Ensure that the required Python packages are installed.
3. Run the Jupyter notebooks provided.

## Contact

For any additional questions or comments, please contact the repository owner.

---

*Note: This project is for educational purposes and the datasets used are fictional.*
