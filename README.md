# UK Housing Analysis

## Description
This project investigates UK house-price trends, regional differences and the relationship between house prices, earnings and GDP per head. 

## Data
The project combines data from the following sources:
- [UK House Price Index](https://www.gov.uk/government/statistical-data-sets/uk-house-price-index-data-downloads-january-2026)
- [Median UK Earnings](https://nmweb.dur.ac.uk/query/construct/summary.asp?mode=construct&version=0&dataset=30)
- [Regional Gross Domestic Product](https://www.ons.gov.uk/economy/grossdomesticproductgdp/datasets/regionalgrossdomesticproductlocalauthorities)
- [UK Population Estimates](https://www.ons.gov.uk/file?uri=/peoplepopulationandcommunity/populationandmigration/populationestimates/datasets/populationestimatestimeseriesdataset/current/previous/v15/pop.csv)

## Methodology
The project follows these stages:

1. Data cleaning and validation
2. Data merging
3. Exploratory Data Analysis
4. Correlation analysis
5. Price-to-earnings ratio analysis
6. Multiple linear regression
7. Multicollinearity analysis using VIF
8. Regression diagnostics

## Exploratory Data Analysis (EDA)
The EDA is split into two parts. The first part is a regional exploration of average house prices, median earnings and median local authority GDP per head from 2002 to 2023. The second part is an exploration of average house price and population across England (as a whole rather than the individual regions), Scotland, Wales and Northern Ireland from 1971 to 2024. Both parts consist of summary statistics, data visualisations (e.g. box plots) and time-series analysis.

## Repository Structure

```text
├── README.md
├── analysis.Rmd
└── data/
    ├── median_earnings.csv
    ├── house_prices.csv
    ├── gdp.csv
    └── population.csv
```
