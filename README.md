# Movies Investment Prediction using a LRM

Provide recommendations to a Producer investor on what movies he should make by building a predictive Linear Regression Model based on historical 5 years data scraped from Box Office Mojo website. 

# Question/need:

What is the framing question of your analysis, or the purpose of the model/system you plan to build?
Our client wants recommendations on what movies he should produce in order to make the most profitable movie in the US(domestic gross). 

Who benefits from exploring this question or building this model/system?
Our client is a prestigious Movies Producer who has reached out to us for Investment recommendations on what movies he should make considering the last 5 years of historical data. He has asked to exclude 2021 and 2020 from the analysis since those years are a bad reference due to the pandemic lookdown. 

# Data Description:

What dataset(s) do you plan to use, and how will you obtain the data?
We will build our dataset by using Beautiful Soup Web Scraping method. We have enough information on this website to build a Predictive model for our client.

What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
We will build a base Linear Regression Model initially using the most correlated numerical features with our Target. We will select those features based on the EDA analysis after the scraping and cleaning process.

If modeling, what will you predict as your target?

Since we want to build a model to predict the most profitable movie production, we will use Domestic Gross as our Target important features to consider in terms of profitability when making a decision on a movie production investment.

# Tools:

How do you intend to meet the tools requirement of the project?
I'll start by scraping the data from Box Office Mojo website by using BeautifulSoup method. Then, will clean and analyze the data on the EDA by using Pandas package. After building a basic Linear Regression model, I am planning to apply some feature engineering methods to improve my model by evaluating the R^. 

Are you planning in advance to need or use additional tools beyond those required?
Initially not, but I might consider using other Web Scraping methods besides Beautiful Soup to scrape additional data from other websites if I need to include other features in my model.
