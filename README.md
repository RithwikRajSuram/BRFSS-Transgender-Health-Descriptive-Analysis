# BRFSS Transgender Health Descriptive Analysis
## 📊 Live Dashboard

[![View Live Dashboard](https://img.shields.io/badge/📊_View_Live_Dashboard-2a78d6?style=for-the-badge)](https://claude.ai/artifact/5sW5w5J1WuJfBDt99yz36p#brfss)

---


## Overview
This project analyzes transgender participants from the 2014 Behavioral Risk Factor Surveillance System (BRFSS). The goal was to clean, recode, and summarize demographic and health-related characteristics using descriptive statistics in R.

## Objective
To create a descriptive statistics table for transgender participants in the 2014 BRFSS dataset, including transition status, days of poor physical health, race/ethnicity, income, education, age, and age category.

## Data Source
Behavioral Risk Factor Surveillance System (BRFSS), 2014  
Dataset used: `transgender_hc_ch2.csv`

## Methods
- Imported the 2014 BRFSS dataset into R
- Filtered participants with transgender status using `TRNSGNDR < 4`
- Selected variables related to transgender status, physical health, income, education, age, and race/ethnicity
- Converted variables into appropriate data types
- Recoded missing values and category labels based on the BRFSS codebook
- Generated descriptive statistics using the `tableone` package
- Summarized participant characteristics in a written interpretation

## Tools Used
- R
- R Markdown
- tidyverse
- tableone
- descr
- labelled

## Key Skills Demonstrated
- Public health data cleaning
- Categorical variable recoding
- Descriptive statistics
- R Markdown reporting
- Codebook-based data preparation
- Health survey data analysis

## Files
- `brfss_transgender_analysis.Rmd` – R Markdown analysis file
- `outputs/` – Generated tables or knitted reports
- `figures/` – Optional visualizations
