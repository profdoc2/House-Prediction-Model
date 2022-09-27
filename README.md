# House-Prediction-Model
Project Overview:
In this project, I predicted future house prices.
I used data from the Federal Reserve, along with house price data from Zillow. 
I merged and combined this data, then used it to train a random forest model. 

Project Abilities:
The model will predict if house prices will increase or decrease in the future. 
I measured error using backtesting, then improved the model with new predictors.
This project can be customised to predict house prices in your metro area if you live in the US.

Below is the description of the data files.
CPIAUCSL.csv - US CPI (inflation measure)
RRVRUSQ156N.csv - rental vacancy rate, quarterly
MORTGAGE30US.csv - mortgage interest rates, weekly
Metro_median_sale_price_uc_sfrcondo_week.csv - median sale price for US houses
Metro_zhvi_uc_sfrcondo_tier_0.33_0.67_month.csv - Zillow home value index


What I learnt:
I discovered new coding practices for data cleaning such as list comprehension.
 I learnt how to merge data sets with panda functions.
I learnt how to create a backtest engine in place of cross validation(as time series data does not function well with the latter), which would result in overfitting. Thus improving model accuracy by lowering bias.

Challenges I came across were:
BUGS! A whole lot of them too! Most of them were irritatingly discrete, a misplaced coma here or an incorrect bracket there. I discovered that reading my code backwards allowed me to better analyse where I could go wrong, making the process smoother.
Another challenge was understanding decision trees intuitively in my machine learning model.
However I do believe understanding its absolute theory is moreso for data engineers.
Despite this obstacle I kept on working on it and I’ll confidently say…  I still dont get it! However I’m glad I got a general hang of it and my code works sufficiently with random forest classifier as my machine learning model.

Next Steps Include:
Researching different algorithms for better fitting models
More prediction based projects focusing on economic subjects. 
Addition of extra independent variables after analysing collinearity.


Credits: Data Quest for project tutorial on youtube.
