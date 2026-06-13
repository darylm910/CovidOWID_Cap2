# COVID Mortality Prediction

## Overview

This project investigates the factors associated with differences in COVID-19 mortality across countries. By combining public health, demographic, economic, healthcare, vaccination, and government policy data, the goal is to identify variables that are strongly associated with COVID-19 mortality and evaluate the ability of machine learning models to predict mortality outcomes.

The project was completed as part of the Springboard Data Science Career Track Capstone Two project.

## Problem Statement

The COVID-19 pandemic produced dramatically different outcomes across countries. While some countries experienced relatively low mortality rates, others suffered substantial mortality despite access to similar scientific knowledge and public health recommendations.

This project seeks to answer the following questions:

* Which country-level factors are most strongly associated with COVID-19 mortality?
* How important were vaccination rates relative to demographic and economic factors?
* Were government policy responses associated with mortality outcomes?
* To what extent can country-level mortality outcomes be predicted using publicly available data?

## Data Sources

### Our World in Data COVID-19 Dataset

https://ourworldindata.org/coronavirus-source-data

Provides:

* COVID-19 cases
* COVID-19 deaths
* Vaccination rates
* Booster rates
* Population characteristics

### World Bank Open Data

https://data.worldbank.org

Provides:

* GDP per capita
* Population density
* Life expectancy
* Healthcare expenditure
* Additional demographic and economic indicators

### Oxford COVID-19 Government Response Tracker

https://www.bsg.ox.ac.uk/research/research-projects/covid-19-government-response-tracker

Provides:

* Government response measures
* School closures
* Workplace restrictions
* Travel policies
* Stringency indices

## Project Structure

```text
covid_mortality_project/

├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── notebooks/
│
├── reports/
│   ├── figures/
│   └── tables/
│
├── src/
│
├── references/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Workflow

1. Acquire data from public sources.
2. Clean and validate individual datasets.
3. Merge datasets using country identifiers.
4. Create an analysis-ready dataset.
5. Perform exploratory data analysis.
6. Develop predictive models.
7. Interpret model results and feature importance.
8. Communicate findings through visualizations and a final report.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Current Status

* [x] Project proposal completed
* [ ] Data collection
* [ ] Data wrangling
* [ ] Exploratory data analysis
* [ ] Feature engineering
* [ ] Modeling
* [ ] Model evaluation
* [ ] Final report

## Author

Daryl Morris

Springboard Data Science Career Track

