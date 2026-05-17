# cs215-final-project
Data analysis of U.S. housing affordability trends, 1984–2024
# The Affordability Gap: U.S. Housing Affordability, 1984–2024

**CS-215 Data Science Final Project | Ananya Mehta | May 2026**

## Project Overview
This project analyzes how U.S. housing affordability has changed over 40 years
using data from the Federal Reserve Bank of St. Louis (FRED). Rather than
relying on a pre-built index, I constructed custom affordability metrics from
three raw data series.

## Research Questions
1. Has the price-to-income ratio grown beyond the conventional 3× benchmark?
2. When has the monthly mortgage payment exceeded 28% of income — and why?
3. Is the 2022–2024 crisis structurally different from the 2008 bubble?

## Key Finding
The current affordability crisis is the worst in 40 years — worse than the
2008 bubble peak. Unlike prior crises which had a single driver (prices or
rates), today's crisis compounds both simultaneously.

## Files
- `housing_affordability.ipynb` — full analysis notebook (run in Google Colab)
- `index.html` — project webpage
- `data/` — raw CSV files from FRED

## Data Sources
- [MSPUS](https://fred.stlouisfed.org/series/MSPUS) — Median Home Sale Price
- [MEHOINUSA646N](https://fred.stlouisfed.org/series/MEHOINUSA646N) — Real Median Household Income
- [MORTGAGE30US](https://fred.stlouisfed.org/series/MORTGAGE30US) — 30-Year Fixed Mortgage Rate

## Tools
Python, pandas, Plotly, Google Colab
