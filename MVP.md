Movies Investment Predictions using a Linear Regression Model
The goal of this project is to provide recommendations to a Producer on what movies he should make by building a predictive Linear Regression Model based on historical 5 years data scraped from Box Office Mojo website.

[](https://github.com/hernantru943/Movies-Investment-Prediction-using-a-LRM/blob/cca03e14b0053c94451ee0ef369ca964e1250178/Screen%20Shot%202021-06-09%20at%201.20.49%20AM.png)
[](https://github.com/hernantru943/Movies-Investment-Prediction-using-a-LRM/blob/cca03e14b0053c94451ee0ef369ca964e1250178/Screen%20Shot%202021-06-09%20at%201.22.29%20AM.png)

To start exploring this goal, I built a linear regression model with only 5 features to describe Box Office Total Domestic Gross as a function of the most important features.

The fist figure is showing the correlation between this 5 features with the Domestic Gross so we were able to identify Opening Gross and Worldwide Gross as the most correlated features with our target.
The second figure depicts the model plotted against the actual predicted target vs True Target and Residual values. The probability plot is displayed on the right side as well.

This partial result suggests that Opening Gross may have a significant positive impact on a film's revenue (Domestic Gross). However, the magnitude of the model's residuals makes it clear that budget is not the only important factor in determining the success of a film.
