# Airbnb-EDA
Prediction of prices of Airbnb's available in England after analysing the data

Interpretation:
----------------------

From the analysis it can be seen that Price value not just depends upon the location, room_type or size but also gets influenced by a lot of other features like:

The quality of pictures, profile pics, etc)
Availability of homes
The number and content of reviews, reviews
Acceptance rate, host response time, etc
Host type (super or normal)
And rest few
These features may not have much impact but might have a substantial influence.

This analysis focuses on providing a price range for a new person to look on Airbnb and identify the price ranges based on the features provided.

At the moment the r2 value is not so efficient which can be improved by including the above mentioned features too with the ones modelling has been done on. This can possibly give a better result.

Run the parameters values to find the best parameter of XGBRegressor.

Also, a k-fold cross verification can be performed to improve the error and also to clarify the training and test dataset in future.
