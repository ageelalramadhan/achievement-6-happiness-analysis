# Achievement 6 – Happiness & Economic Factors

This project analyzes global happiness data from the 2019 World Happiness Report to examine how selected socio-economic factors relate to reported well-being across countries. In addition, a standalone time-series analysis using U.S. unemployment data is included to demonstrate analytical techniques for temporally ordered data.

The work was completed as part of Achievement 6 using Python for data analysis and Tableau for visualization.

📖 **Case study writeup:** [ageelalramadhan.github.io/happiness-case-study.html](https://ageelalramadhan.github.io/happiness-case-study.html)

---

## Project Objectives

- Explore global patterns in happiness scores
- Examine relationships between happiness and selected socio-economic factors:
  - GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption
- Estimate the strength of association between each factor and happiness scores
- Segment countries into well-being profiles via K-Means clustering
- Demonstrate differences between cross-sectional and time-series analytical methods
- Communicate insights through clear visualizations

---

## Data Sources

**Happiness Analysis**
- World Happiness Report (2019)
- One row per country (156 countries)
- 9 columns: overall rank, country, happiness score, and 6 numeric predictors

**Time-Series Demonstration**
- U.S. Unemployment Rate (FRED series `UNRATE`)
- Monthly observations
- Used to illustrate trend analysis, stationarity testing (Augmented Dickey-Fuller), and autocorrelation diagnostics

---

## Project Structure
