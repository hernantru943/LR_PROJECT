# Movies Investment Prediction using a LRM

Provide recommendations to a Producer on what movies he should make by building a predictive Linear Regression Model based on historical 5 years data scraped from Box Office Mojo website. 

# Question/need:

What is the framing question of your analysis, or the purpose of the model/system you plan to build?
Our client wants recommendations on what movies he should produce in order to make the best possible revenue.

Who benefits from exploring this question or building this model/system?
Our client is a prestigious Movies Producer who has reached out to us for Investment recommendations on what movies he should make next.  

# Data Description:

What dataset(s) do you plan to use, and how will you obtain the data?
We will build our dataset by using Web Scraping methods.

What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with?
We intend to analyze the correlation among several numerical features such as Opening Gross and number of Theaters in order to build the most predictive LR model.  

If modeling, what will you predict as your target?

Our target is to build the most accurate model that can help our client to identify the most important features to consider in terms of profitability when making a decision on a movie production investment.

# Tools:

How do you intend to meet the tools requirement of the project?
I'll start by scraping the data from Box Office Mojo website by using BeautifulSoup method. Then, clean and analyze my data with the EDA process by using Pandas package. Finally, I'll evaluate the correlation among the features to build a LR model as well as fit, train and test my model considering the final R^ factor.

Are you planning in advance to need or use additional tools beyond those required?
Initially not, but I might consider using other Web Scraping methods besides Beautiful Soup if necessary.
