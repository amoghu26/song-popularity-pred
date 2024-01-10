# Predicting Song Popularity
The goal of this project was to try to find a trend between the popularity score (0-100) of a song and its measurable features such as its duration, acousticness, tempo, speechiness, etc. My first step was to clean the data in the song_data.csv file by removing the major outliers that would skew the data. I then implemented 4 separate models for this project: a linear regression model, a polynomial regression model, a random forest regression model, and a neural network model. Each model's accuracy is displayed below using error metrics such as mean absolute error, mean squared error, root mean squared error, and r^2 value. Additionally, each model's results are displayed in a scatter plot which displays the predicted score vs actual score for the popularity of 1000 songs in the data set. A perfect result would have a line of best fit that has a slope of 1 and intersects the y-axis at x = 0, or in simpler terms, a line with equation y = x, for optimal accuracy.

# Linear Regression Model:

<img width="431" alt="Screenshot 2024-01-09 at 1 21 14 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/5f86f477-b1b7-4f1f-a02b-ac8098502239">

Mean Absolute Error: 17.19050982819729

Mean Squared Error: 462.7021257197936

Root Mean Squared Error: 21.510511981814698

R-squared: 0.019700695171400162





# Polynomial Regression Model (4 Degrees):

<img width="436" alt="Screenshot 2024-01-09 at 1 20 57 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/b2f8ac32-54f7-4e0b-a357-ecd7a34a519a">

Mean Absolute Error: 17.79396936738929

Mean Squared Error: 1235.659472355967

Root Mean Squared Error: 35.151948343668906

R-squared: -1.6179177799779252




# Random Forest Regression Model:

<img width="434" alt="Screenshot 2024-01-09 at 1 20 43 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/0fc20af3-b47e-4158-a9f6-1a80ba58df8e">

Mean Absolute Error: 11.306770604083823

Mean Squared Error: 258.7561170532696

Root Mean Squared Error: 16.08589808040787

R-squared: 0.4517888992343203






# Neural Network Model:

<img width="429" alt="Screenshot 2024-01-09 at 1 20 31 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/94d14c4c-b475-4c1e-b6d1-b95c1b7fae64">

Mean Absolute Error: 15.899743285970903

Mean Squared Error: 405.184091347732

Root Mean Squared Error: 20.129185064173164

R-squared: 0.1415607126120494


# Results 
As displayed by the results above, the random forest regression model found a moderate correlation between the popularity scores of the songs in the dataset and their measurable features. It boasts a mean absolute error of 11.307, which is over 4 lower than any other model! Additionally, its graph's line of best fit is much closer to the desired y = x line than any of the other models with an r^2 value of 0.452. So, we can conclude that the random forest regression model most accurately predicts song popularity values for this data set.
