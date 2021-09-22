Hello to the Offensive Coaching Staff of the New York Jets,

I want to start by saying I am honored to be invited to work with you all. Since I was a kid, I have cared deeply about the sport of football and the Jets, and the opportunity to combine that passion with my love for Data Science is very fulfilling. I look forward to diving into this offensive analysis with you all and hopefully getting this season on the right track.

Below, you will find a high-level blueprint of the analysis I will conduct, including the purpose of the analysis, the data being considered, and some of the tools I will use. Happy to clarify any of the below further on a call.

## **Purpose of Analysis** - Maximize Offensive Efficiency
Whenever I engage in data analysis for a client, I always make sure that the goal is clear and measurable. This both provides the end user with confidence in the process and enables them to make optimal decisions using the data. In the case of the Jets, my goal is to maximize offensive efficiency, as defined by Football Outsider’s DVOA (Defense-adjusted Value Over Average). This analysis will aid our offense in making the optimal decisions with respect to offensive efficiency. 

## **Data Being Examined** - Pro Football Reference & Football Outsiders
Any model we create is only as strong as the data we provide to it. For this analysis, I will be analyzing data from https://www.pro-football-reference.com/ and https://www.footballoutsiders.com/. Pro Football Reference will provide us with most, if not all, of the feature data needed for this linear regression analysis. Football Outsiders has a comprehensive, solid efficiency definition in its DVOA ranking that I will use for the target of the regression. This will enable us to track relationships between various features and the offensive efficiency they produce. 

## **Data Analysis Tools**

**Beautiful Soup / Selenium**- Web scraping tools that will enable me to pull necessary data for analysis  
**Pandas** - DataFrame tool that will enable me to organize data prior to analysis  
**Scikit-learn** - Python Machine Learning library that will enable me to run linear regressions  
**Matplotlib / Seaborn** - Data visualization tools that will enable me to present the results in a clear manner  


## **First Deliverable** - MVP Goal
On Tuesday (9/28) at 6 pm EST, I will deliver my first pass at this model, focused on showing the barebones of this analysis. This includes having scrapped data for at least one team in the league over the span of 5 years, and running a linear regression on some basic features in comparison to the DVOA target. This will enable us to begin to hone in on how effective the analysis can be and enable us to pivot as necessary.

Thank you for your trust in me, and I look forward to working together in the coming weeks.

Best,

Michael
