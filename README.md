# stock_prediction

![alt text](https://github.com/mitty4/[stock_prediction/blob/master/image.jpg?raw=true)



Stock Price Prediction
By: Mitchell LaBauve




Problem Statement:
can time series analysis and various machine learning algorithms (neural networks, decision trees, linear regression) paired with unique feature engineering (RSI, MACD, SMA) uncover a secret of investing?

Context
An investor is looking to find an investment strategy in the stock market. He wants to know if historical data like prices and stock fundamentals can be used to confidently predict the market so he can make better investments. The strategy starts by taking historical data then use a time series analysis to attempt to predict the movement of a stock’s price. Some possible features to engineer are RSI, MACD, SMA.

Success Criteria
Success in terms of this project would mean that we can ultimately predict the price of a stock by only using historical prices and company fundamentals by 95% confidence interval. 

Scope
The scope of this project includes the data from Kaggle.com and nothing else for its first iteration. In the future, there will be room to expand. 

Constraints
The constraints of this project are more about the possibility of producing a valid model. A big question is do we have enough data to actually predict the fluctuations in the market or will we need to iterate the project with new data? Also, there is petabytes of data from the stock market so we are only focusing on a fraction of the available data, which may not give us the intended result.


Stakeholders
The stakeholder for this project will be the single investor interested in employing a successful model.

The Data
The data will be provided by a Kaggle data set (https://www.kaggle.com/dgawlik/nyse). The entire set of data is held across 4 csv files that amount to 100MB. In total, there are 101 columns of data to work with and 851k rows of data. The majority of the data comes in numerical form other than the company descriptions. We will be predicting prices so they will be continuous floats. The data will more than likely have very few null values, if any, due to the nature of the data’s origin.

Final Products
The end product will be a PDF presenting the findings. For example, if predicting the prices is not possible then the PDF will show graphs with explanations of what was tried and its results, then there will be an outline for what else could be tried. Or, if the results are positive then the PDF will show what was found and how confidently it can be used.

Note:
Because we are working trying to predict floats, we can use some models such as linear regression, MLP, decision trees and others, but that will only come after cleaning, exploring the data and creating any new features that uncover patterns. 

Off we go!

