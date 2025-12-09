# World-Happiness-Report-EDA
Exploratory Data Analysis of a World Happiness Report using R and tidyverse.

Author: Joshua Kohlmeyer
Tools: R, Tidyverse, RMarkdown, Git
Dataset: World Happiness Report 2024 (source: https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2024)
Countries: 143
Features: 11

Project Overview

This project presents a full exploratory data analysis (EDA) of the 2024 World Happiness Report. The objective is to investigate the main factors associated with national happiness and to apply a complete real-world data analysis workflow using R.

The analysis includes data loading, cleaning, distribution analysis, outlier detection, correlation analysis, and interpretation of key relationships.

Dataset Description

The main variables used in the analysis are:

ladder_score – Overall happiness score

gdp – Log GDP per capita

life_expectancy – Healthy life expectancy

social_support – Perceived social support

freedom – Freedom to make life choices

generosity – Generosity score

corruption – Perceived corruption

dystopia_residual – Unexplained component of happiness

Analysis Workflow

Loaded and cleaned the dataset in R

Renamed variables for improved readability

Analyzed distributions using histograms

Detected outliers using boxplots

Constructed a correlation heatmap

Interpreted statistical relationships in practical terms

All analysis was performed using the tidyverse ecosystem and documented using RMarkdown.

Key Findings

Strongest drivers of happiness:

GDP per capita

Healthy life expectancy

Both variables show very strong positive correlations with happiness.

Weakest relationship:

Generosity

Generosity shows near-zero correlation with happiness at the country level.

Negative relationship:

Corruption

Higher perceived corruption is associated with lower happiness.

Distributions and outliers:

Happiness and GDP show the widest spread and strongest outliers.

Corruption and generosity show much tighter distributions.

Core Insight

National happiness is driven primarily by economic conditions and population health, while social generosity plays a minimal role at the country level. Corruption consistently reduces well-being across countries.

Technology Used

R

tidyverse

RMarkdown

Git and GitHub

Repository Structure

World-Happiness-Report-eda.Rmd

data.csv

README.md

World-Happiness-Report-EDA.Rproj

Contact

For collaboration or questions:

LinkedIn: (Add your LinkedIn here)

GitHub: (This repository)
