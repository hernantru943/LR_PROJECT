Predictive Model Box Office DomesticGross by Linear Regression
Hernan Trujillo

Abstract:
The purpose of the model I plan to build is to determine which movies will realize the highest domestic gross. I worked with box office and movie profile data provided by Box Office Mojo and applied multiple tools/analyses including web scrapping packages, python packages, visual tools, and regression models and validations. After analyzing the data, I determined the key features of movies that would maximize domestic gross and yield the highest return for movie producer.

Design:
The project’s goal is to help a movies producer with a predictive model to identify the movies and productions he must invest in in order to be successful. 

Data:
The dataset is gathered from Box Office Mojo with 15 features in total and 1000 movies or observations, 4 of which are numerical. The time period of the data is the last 5 years, from 2015 until 2019. In order to prevent outliers, I decided to exclude 2020/2021 (Pandemic crisis) from my 5 years analysis. Some of the features included in the analyses are domestic gross, year, budget, and running time, as well as widest release. The rest of the data features are categorical, which includes ratings, and distributors. Overall, I was selective on the features that were chosen and I did not include all features.

Methodology:
Web Scrapping

I Used BeautifulSoup to compile data, from one page and using loops and functions to collect data from other pages (Pipeline)

Linear Regression Modeling

EDA: Cleaning the data starting by excluding all null values. The mayority were from budget which will be crucial on my analysis. Then, I displayed a pairplot to identify correlations with the target and also amog other features.
I ran separated analysis for Distributors and Genres to choose the features with the highest correlation for my model.
I ran  the base line linear regression model.
I did the train test split on Simple Linear Regression 
Feature engineering (Polynomial)

I did the train test split and put it into the linear regression 

To compare RidgeCV, I did LassoCV to perform regularization on the same existing model

Tools:


Web Scrapping Packages: BeautifulSoup Python Packages: numpy, pandas Visual Tools: pairplot, seaborn, matplotlib Regression Models & Validations: • Linear Regression o import statsmodels.api as sm o from sklearn.linear_model import LinearRegression, RidgeCV, LassoCV o from sklearn.preprocessing import StandardScaler, PolynomialFeatures • Train test split o from sklearn.model_selection import train_test_split • Cross Validations o from sklearn.model_selection import cross_val_score

