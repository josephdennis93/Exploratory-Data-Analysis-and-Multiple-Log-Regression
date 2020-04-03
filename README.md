A python 3 workbook containing an exploratory analysis of the data scraped from a Brazillian real-estate website by kaggle user Rubens Junior (https://www.kaggle.com/rubenssjr/brasilian-houses-to-rent), as well as an attempt at fitting a regression model to the data in order to allow the prediction rental property prices.

After visualising the data and trimming off the outliers, a multiple Log regression was performed, which could very accurately predict the rental prices of lower-cost properties, but failed to model the rental prices of more expensive properties (~25-30% error @ 50% percentile). 

This suggests that while total floor space, the number of rooms, etc are good predictors for cheap apartments, there are some other major factors effecting the price of more expensive properties, perhaps the neighbourhood, type of apartment building, or accessibility of utilities and public transport.
