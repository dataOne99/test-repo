Cs539: Machine Learning
=========
# Project Final - World Happiness

## OVERVIEW
With the advent of the internet, cell phones, computers, and air travel. We see that the world view is becoming smaller. Issues in one country can have an impact on a neighboring country or a country across the ocean. An unhappy country can affect their internal stability as well as the world. It is therefore important to understand what affects the happiness of a country. Third World countries are most vulnerable in the happiness arena. This is why this study will concentrate on these countries and how young people affect the overall happiness of a country. Third World countries have a higher and increasing population of young adults. Data for this study was collected from the Databank World Bank Org. The study undertaken used machine learning regression models to answer the question whether more young adults in a country can predict a higher happiness score for the country. Though there was indication that the percentage of young adults did affect the happiness  score of a country, this affect was less than 10%.

## Project Description

MOTIVATION
Third World countries have a higher and increasing population of young adults. Nigeria has 1 of the largest megacities in the world with an infrastructure that is failing to keep pace with the explosive growth. The world population is expected to grow to 9.9 billion by 2050 [ref 9]. The question that looms is “how will the world cope with this massive population.” The advent of the World Happiness survey is an attempt to try to get a handle on what makes a country happy and hopefully this will translate to the country’s stability. This is an issue that affects all living on spaceship - earth. This study looks at how young adults affect a country’s happiness score. 

AIMS
The goal was to determine if there was a causal relationship between the increase in the number of young adults (20 – 24) in countries deemed low-income (GDP < 1.0 from the Happiness Survey), and their respective country’s happiness score in the World’s Happiest Survey in the period  from 2015 – 2019 ? If more young people increase the happiness in a country, it is probable that these countries will experience stability which would lead to growth and prosperity for their citizens.

DATA SOURCES
I used the datasets from the World Happiness Report [Ref 1]. The dataset is 38k and spans the period 2015-2019. The factors listed in the dataset are as follows: economy, health, freedom, trust, generosity, and family. The features, GPD per capita, life expectancy, and young adults (20-24) were extracted from the World Data Bank organization (years: 2015-2019) and combined with the World Happiness Report data
Data locations:
1.	DataSet:World Happiness Report. https://www.kaggle.com/datasets/unsdsn/world-happiness
2.	World Data Bank: https://databank.worldbank.org/source/world-development-indicators#

## Methods
The analysis included feature engineering, four types of regression models, and various performance evaluations for the models. The percentage of young adults (20-24), an added feature, became a predictor variable in this study. The raw data for the GDP per capita and Life Expectancy were also features added. The four regression models chosen 
were: simple Linear regressor, Ridge regressor, Gradient boosting regressor and Random Forest regressor. The first approach was to begin with a simple model and observe the results. An ensemble approach was chosen for the second and third models. The Ridge regression model was added since it handles independent variables that are highly correlated. Since, the GDP per capita and the Life Expectancy variables were highly correlated. The cross-validation score was used for the comparison of the models.  A comparison of the models was illustrated by box plots as well. The Random Forest regressor model performed the best on the data. 


## Conclusion
We see a minor change when the percent youth feature is removed from the four models. In this study, the percentage of youth has negligible influence on the country’s happiness score. Though this study was not able to show a strong causal relationship between young adults and a happiness score, there will be more young adults worldwide as the world population ages. Their happiness/well-being will certainly have a profound effect on the world stage.






