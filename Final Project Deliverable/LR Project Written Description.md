# Predicting NFL Offensive Efficiency (DVOA)
Michael Kamel

## Abstract
The goal of this analysis was to utilize linear regression models to predict an NFL team’s DVOA (Defense-adjusted Value Over Average) in order to identify patterns exhibited by successful teams. I analyzed 27 seasons worth of data provided by Pro Football Reference and Football Outsiders and tested multiple types of linear regression models in order to tackle this problem.

## Design
This need for this project stems from the New York Jets’ recent struggles offensively over the past 5 years. The team is significantly below average in most metrics, and their record is evidence of this. This led me to my analysis, which was to study key offensive metrics and their relationship to DVOA. A better grasp on these relationships could potentially help the Jets frame their rebuilding process appropriately, both in terms of coaching and resources expended. 

## Data
The primary source of my data was gathered from Pro Football Reference via web scraping. I utilized 27 years of football data, amounting to 851 data points to analyze. The features I used can be categorized in 3 ways: Play call per Down, Play call per Game Situation (winning, losing, or tied), and 1st down Conversion Rates. The other data source was from Football Outsiders, in which I utilized their DVOA metric as my target variable. This is a widely accepted metric to rate teams in comparison to a baseline. 

## Algorithms


## Tools
BeautifulSoup & Selenium for Web Scraping
Pandas for data analysis
SciKit Learn for machine learning models
Matplotlib & Seaborn for data visualization

## Communication
After conducting my analysis, I shared my findings with my cohort via this [presentation](link).
