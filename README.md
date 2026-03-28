# Malaria Temporal, Seasonal and Climatic Dynamics in Adétikopé, Togo (2022-2024)

## Project Overview

This repository contains the full analytical workflow used to describe the temporal, seasonal, climatic, and entomological dynamics of malaria transmission in Adétikopé (Togo) between 2022 and 2024.

The project was conducted as part of a Master’s thesis in One Haealth.
All analyses were implemented in Python based on sentinel surveillance, meteorological, and entomological data.

## Academic Context

•	Project owner & thesis author: ATTISSO

•	Degree: Master’s thesis (One health)

•	Institution: University of Lomé

•	Study period: 2022–2024

•	Study area: Adétikopé, Togo

### This repository serves as the computational and analytical support for the thesis.

### Contributions

•	Protocol conception, data analysis, statistical modeling, visualization, scientific interpretation: Conducted by the repository contributor (code author)

•	Conceptualization, data ownership, and scientific interpretation: ATTISSO

### This repository reflects a collaborative academic work, with a clear distinction between scientific ownership and technical implementation.

### Objectives

The main objectives of this project are to:

•	Describe the monthly, seasonal, and interannual evolution of confirmed malaria cases and prevalence.

•	Compare malaria prevalence across transmission seasons (high, transition, low) and years using two-way ANOVA.

•	Explore graphical and statistical relationships between climatic variables (rainfall, temperature, humidity) and malaria indicators.

•	Model malaria case counts during the low transmission season using Poisson and Negative Binomial regression.

•	Describe entomological characteristics of larval breeding sites associated with malaria transmission.

Data Description

The main dataset used is:
Clean_data_for_M._ATTISSO 06 01 2026.xls

It includes:

•	Monthly malaria indicators (suspected cases, confirmed cases, prevalence)

•	Age stratification (<5 years and ≥5 years, including pregnant women)

•	Transmission season classification

•	Meteorological variables:

o	Rainfall (mm)

o	Mean temperature (°C)

o	Relative humidity (%)

Data are not publicly shared due to confidentiality and ethical considerations.

## Analytical Workflow
The code implements:
1.	Data import, cleaning, and time variable construction
2.	Descriptive statistics and summary tables (by year, season, age group)
3.	Time-series visualizations with seasonal background shading
4.	Two-way ANOVA on prevalence indicators with assumption checks
5.	Tukey post-hoc comparisons
6.	Climate–malaria association analyses (Spearman correlations with lags)
7.	Poisson regression with meteorological adjustment
8.	Overdispersion testing and Negative Binomial regression

All figures are generated in publication-ready format.

## Tools and Libraries

Analyses were conducted using Python (Google Colab compatible):

•	pandas

•	numpy

•	matplotlib

•	seaborn

•	statsmodels

•	scipy

Initial data cleaning was performed using SPSS 27.

## Outputs

The repository produces:

•	High-resolution figures (PNG, 300 dpi)
•	Descriptive summary tables
•	ANOVA and post-hoc outputs
•	Regression model summaries with rate ratios and 95% confidence intervals

## Intended Use
This repository is intended for:
•	Academic evaluation (Master’s thesis)
•	Epidemiological surveillance research
•	Reproducible public health analysis
•	Training in applied biostatistics and epidemiology

## Citation

If this repository or code is reused, please cite the thesis author:
ATTISSO, KANDJONI Y. (2026). Temporal, seasonal and climatic dynamics of malaria transmission in Adétikopé, Togo (2022–2024). Master’s thesis, One health

## Contact

For scientific questions related to the study:

•	Thesis author: ATTISSO, Master of Science in One Health, University of Lomé, Togo.

For technical questions related to the code:

•	Code contributor: KANDJONI Yendouname, Master of Science in Biostatistics, SRM Institute of Science and Technology (SRM IST), India.
