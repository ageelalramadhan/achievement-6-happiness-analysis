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

```
achievement-6-happiness-analysis/
├── Data/
│   └── 2019.csv
├── Notebooks/
│   ├── Exploratory_Analysis.ipynb
│   └── Modeling_Methods_Overview.ipynb
├── Tableau/
│   └── tableau_link.txt
└── README.md
```

---

## Notebooks Overview

### Exploratory_Analysis.ipynb
- Data inspection and validation
- Selection of relevant numeric variables
- Pearson correlation matrix and heatmap
- Scatter plots with regression trends
- Pair plot of well-being indicators
- Categorical analysis (low / medium / high happiness groups)
- Exploratory insights motivating modeling choices

### Modeling_Methods_Overview.ipynb
- Overview of modeling approaches applied after exploration
- Univariate linear regression (cross-sectional happiness data)
- K-Means clustering at k = 3 (multivariate country profiles)
- Time-series analysis using U.S. unemployment data (trend visualization, ADF stationarity testing, autocorrelation diagnostics)
- Consolidated discussion of insights, limitations, and next steps

*Note: The time-series analysis is included as a methodological demonstration and is not directly integrated with the cross-sectional happiness dataset.*

---

## Tools & Libraries

Python · Pandas · NumPy · SciPy · Matplotlib · Seaborn · scikit-learn · statsmodels · pandas_datareader · Tableau

---

## Tableau Visualization

Key findings from the happiness analysis are presented in an interactive Tableau story, including:

- Global distribution of happiness scores (choropleth)
- Relationships between happiness, GDP per capita, and social support
- Summary insights, limitations, and next steps

**Tableau Public link:**
[Achievement 6 — Happiness & Economic Factors](https://public.tableau.com/views/Achievement6HappinessEconomicFactors/Achievement6HappinessEconomicFactors)

---

## Limitations

- Happiness data represents a single year and does not capture changes over time
- Observed associations do not imply causation
- Linear regressions in this project are univariate; relative contributions of correlated predictors cannot be separated without a multivariate model
- Clustering results depend on subjective modeling choices (choice of k, feature selection, scaling)
- Time-series results are illustrative and not comparable to cross-sectional happiness outcomes

---

## Next Steps

- Extend regression analysis to include multiple predictors simultaneously
- Validate clustering results using alternative clustering methods (hierarchical, DBSCAN)
- Incorporate longitudinal happiness data to enable true time-series modeling
- Explore forecasting models (e.g., ARIMA) in greater depth for time-series datasets

---

## Author

**Ageel Alramadhan** — Data Analyst, Hamburg
[Portfolio](https://ageelalramadhan.github.io) · [LinkedIn](https://www.linkedin.com/in/ageel-alramadhan/) · [GitHub](https://github.com/ageelalramadhan)
