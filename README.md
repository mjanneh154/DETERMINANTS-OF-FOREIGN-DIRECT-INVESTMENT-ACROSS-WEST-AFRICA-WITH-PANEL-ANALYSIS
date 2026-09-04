# DETERMINANTS-OF-FOREIGN-DIRECT-INVESTMENT-ACROSS-WEST-AFRICA-WITH-PANEL-ANALYSIS
This project set to explore the Macroeconomics Determinants of  Foreign Direct Investment across 16 West African Countries.

Determinants of Foreign Direct Investment in West Africa.Panel Data Analysis Using Python

# Overview

This project examines the economic factors associated with Foreign Direct Investment (FDI) in selected West African countries using panel-data econometric methods.

The analysis uses World Bank World Development Indicators (WDI) and applies pooled OLS, country fixed effects, and country-and-year fixed effects.

Research Question

What economic factors are associated with Foreign Direct Investment (FDI) in selected West African countries?

# Data

* Source: World Bank World Development Indicators (WDI)
* Original sample: 16 West African countries
* Data structure: Country-year panel data
* Dependent variable: Foreign Direct Investment (FDI), net inflows (% of GDP)

The explanatory variables include inflation, trade openness, gross capital formation, internet usage, labor-force participation, population growth, GDP growth, and the official exchange rate.

# Methodology

The project follows these main steps:

1. Data cleaning and preparation
2. Descriptive statistics
3. Exploratory data visualization
4. Initial 18-variable fixed-effects model
5. Multicollinearity analysis using VIF
6. Reduced model specification
7. Pooled OLS estimation
8. Country fixed-effects estimation
9. Country and year fixed-effects estimation
10. Clustered standard errors
11. Model comparison and interpretation

# Model Diagnostics

The analysis checks for:

* Multicollinearity: Variance Inflation Factors (VIF)
* Heteroskedasticity: addressed through country-clustered standard errors
* Serial correlation: within-country dependence is accounted for through country-clustered standard errors
* Poolability: F-tests are used to assess whether pooled OLS is appropriate relative to fixed effects

The initial 18-variable model produced a high within R² of approximately 0.7991, but showed substantial multicollinearity. A reduced specification was therefore considered.

# Main Results

The reduced country fixed-effects model with country-clustered standard errors produced a within R² of approximately 0.4788.

# The main findings were:

* Population growth: negative and statistically significant (p = 0.0016)
* Trade openness: positive, with borderline statistical significance at the 10% level (p = 0.0550)
* Inflation: not statistically significant
* Gross capital formation: not statistically significant after clustering
* Internet usage: not statistically significant
* Labor-force participation: not statistically significant
* GDP growth: not statistically significant
* Official exchange rate: not statistically significant

These results represent statistical associations and should not be interpreted as causal effects.

# Key Takeaway

The analysis demonstrates how panel-data methods can be used to account for unobserved country-specific characteristics when studying FDI across countries.

The results also demonstrate the importance of model diagnostics: a higher R² does not necessarily imply a better econometric model when issues such as multicollinearity are present.

# Limitations:

* The final estimation sample is relatively small.
* The number of country clusters is limited.
* Missing data reduce the original 16-country sample.
* Some explanatory variables exhibit moderate multicollinearity.
* Important FDI determinants may be omitted.
* The analysis identifies associations rather than causal relationships.

# Tools

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Linearmodels
* Jupyter Notebook

# Visualizations
![FDI TREND OVER YEARS](fdi_trend)
