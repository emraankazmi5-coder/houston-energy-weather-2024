# How Temperature Drives Houston's Energy Use (2024)

An R analysis of how temperature affects **monthly electricity and natural gas consumption in Houston, TX** in 2024, combining NOAA daily weather data with monthly utility consumption data.

## Research question
How does temperature influence Houston's monthly electricity and natural gas consumption?

## Key findings
| Relationship | Correlation (r) |
|---|---|
| Temperature ↔ Electricity | **+0.88** (strong positive: hotter months, more A/C load) |
| Temperature ↔ Natural gas | **−0.91** (strong negative: colder months, more heating) |
| Electricity ↔ Natural gas | **−0.91** (strong negative: seasonal substitution) |

## Methods
Data cleaning and merging · descriptive statistics · ggplot2 visualizations · linear regression models · correlation analysis

## Tech stack
R · R Markdown · tidyverse · ggplot2

## Files
| File | Description |
|---|---|
| `houston_energy_analysis_2024.Rmd` | Full reproducible analysis |
| `houston_energy_analysis_2024.html` / `.pdf` | Rendered report |
| `data/houston_energy_weather_2024.csv` | Merged monthly dataset (main input) |
| `data/houston_monthly_electricity_2024.csv`, `data/houston_monthly_gas_2024.csv` | Monthly consumption |
| `data/houston_noaa_daily_2024.csv` | NOAA daily weather (365 days) |

## How to run
Open `houston_energy_analysis_2024.Rmd` in RStudio and click **Knit**.

---
*Data analytics project – M.S. Data Science, University of St. Thomas (Houston).*
