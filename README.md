# Predicting Song Popularity
The goal of this project was to try to predict the popularity score (0-100) of a song based on its measurable features such as the song's duration, acousticness, tempo, speechiness, etc. I implemented 4 separate models for this project: a linear regression model, a polynomial regression model, a random forest regression model, and a neural network model. Each model's accuracy is displayed using error metrics such as mean absolute error, mean squared error, and root mean squared error. Additionally, each model's results are displayed in a scatter plot which displays the predicted score vs actual score for the popularity of 1000 songs in the data set. We are looking for a line of best fit that has a slope of 1 and intersects the y-axis at x = 0 for optimal accuracy.

# **Linear Regression Model:**

<img width="431" alt="Screenshot 2024-01-09 at 1 21 14 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/5f86f477-b1b7-4f1f-a02b-ac8098502239">

Error Metrics:

Mean Absolute Error: 17.19050982819729

Mean Squared Error: 462.7021257197936

Root Mean Squared Error: 21.510511981814698





# **Polynomial Regression Model (4 Degrees):**

<img width="436" alt="Screenshot 2024-01-09 at 1 20 57 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/b2f8ac32-54f7-4e0b-a357-ecd7a34a519a">

Error Metrics:

Mean Absolute Error: 17.79396936738929

Mean Squared Error: 1235.659472355967

Root Mean Squared Error: 35.151948343668906






# **Random Forest Regression Model:**

<img width="434" alt="Screenshot 2024-01-09 at 1 20 43 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/0fc20af3-b47e-4158-a9f6-1a80ba58df8e">

Error Metrics:

Mean Absolute Error: 11.306770604083823

Mean Squared Error: 258.7561170532696

Root Mean Squared Error: 16.08589808040787






**Neural Network Model:**

<img width="429" alt="Screenshot 2024-01-09 at 1 20 31 AM" src="https://github.com/amoghu26/song-popularity-pred/assets/69988876/94d14c4c-b475-4c1e-b6d1-b95c1b7fae64">

Error Metrics:

Mean Absolute Error: 15.899743285970903

Mean Squared Error: 405.184091347732

Root Mean Squared Error: 20.129185064173164


