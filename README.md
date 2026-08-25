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
The EDA is split into two parts. The first part examines average house prices, median earnings and median local authority GDP per head across 12 UK regions from 2002 to 2023. The second examines average house price and population across England, Scotland, Wales and Northern Ireland from 1971 to 2024. 

Both analyses use summary statistics, data visualisations and time-series analysis to investigate regional differences and changes over time.

## Report
- `Housing_analysis.Rmd` – R Markdown source code
- `[Housing_analysis.pdf](Housing_analysis.pdf)` – full analysis report – knitted PDF report

The report consists of the full analysis: results, discussion, key findings, limitations and conclusion.

## Repository Structure

```text
summer-python-project/
|
|--- data/
|   |--- gdp.csv
|   |--- house_prices.csv
|   |--- median_earnings.csv
|   |--- population.csv
|
|--- .gitignore
|--- Housing_analysis.Rmd
|--- Housing_analysis.pdf
|--- README.md
```
