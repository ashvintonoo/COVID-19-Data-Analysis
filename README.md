# COVID-19 Data Analysis

An early learning project exploring whether a country's economic and social indicators relate to how fast COVID-19 spread in early 2020.

## Data
- `covid19_Confirmed_dataset.csv`: daily confirmed cases by country, Jan to Apr 2020
- `worldwide_happiness_report.csv`: GDP per capita, social support, healthy life expectancy and freedom by country

## Approach
1. Aggregated confirmed cases by country
2. Calculated each country's maximum daily infection rate
3. Joined it with the happiness report indicators
4. Measured correlations and plotted regressions for each indicator

## Findings
GDP per capita had the strongest positive correlation with the maximum infection rate. This is a correlation, not a cause: wealthier countries also tested more and reported more consistently, so part of the effect is likely detection rather than higher real infection.

## Tools
Python, pandas, NumPy, seaborn, matplotlib, Jupyter
