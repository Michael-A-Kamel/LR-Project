# Predicting NFL Offensive Efficiency (DVOA)
Michael Kamel

## Abstract
The goal of this analysis was to utilize linear regression models to predict an NFL team’s Offensive Efficiency, represented by DVOA (Defense-adjusted Value Over Average), in order to identify patterns exhibited by successful teams. I analyzed 27 seasons worth of data provided by Pro Football Reference and Football Outsiders and tested multiple types of linear regression models in order to tackle this problem.

## Design
The need for this project stems from the New York Jets’ recent struggles on offense over the past 5 years. The team is significantly below average in most metrics, and their record is evidence of this. This led me to my analysis, which was to study key offensive metrics and their relationship to DVOA. A better grasp on these relationships could potentially help the Jets frame their rebuilding process appropriately, both in terms of coaching and resources expended. 

## Data
My primary data source was gathered by web scraping Pro Football Reference. I utilized 27 years of football data, amounting to 851 data points to analyze (each teams' season being one data point). The features I used can be  broadly categorized in 3 ways: Play call per Down, Play call per Game Situation (winning, losing, or tied), and 1st down Conversion Rates. My other data source was scraped from Football Outsiders, in which I utilized their DVOA metric as my target variable. This is a widely accepted metric to rate teams in comparison to a baseline. 

## Algorithms
Linear Regression, Lasso Regression, Ridge Regression, Polynomial Regression, and Polynomial Lasso Regression were all considered before choosing to use Linear Regression. Most of the models resulted in very similar validation and test R^2 scores, leading me to choose the model with the simplest breakdown and highest interpretability. Polynomial Lasso Regression was essentially even with Linear Regression in terms of results, but I choose Linear Regression for its more interpretable coefficients. I had tried a couple versions of feature engineering, but was only able to find very slight increases to R^2 with variables that again wouldn't be very interpretable. My Linear Regression Validation R^2 score was .7723 and my R^2 Test score was .7359.

## Tools
**Pandas** - Data Munging  
**BeautifulSoup / Selenium** - Web Scraping  
**scikit-learn** - Machine Learning Models   
**Matplotlib / Seaborn** - Data Visualization

## Communication
After conducting my analysis, I shared my findings with my cohort via this [presentation](https://github.com/Michael-A-Kamel/LR-Project/blob/main/LR%20Project%20Presentation.pdf).
