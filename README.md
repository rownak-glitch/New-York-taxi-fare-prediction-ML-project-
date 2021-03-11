# New-York-taxi-fare-prediction-ML-project-
# Dataset Link -https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data

# 1.test.csv 
Input features for the test set (about 10K rows). Your goal is to predict fare_amount for each row.

# 2.sample_submission.csv 
a sample submission file in the correct format (columns key and fare_amount). This file 'predicts' fare_amount to be $11.35 for all rows, which is the mean fare_amount from the training set.

# Features-
1.pickup_datetime - timestamp value indicating when the taxi ride started.

2.pickup_longitude - float for longitude coordinate of where the taxi ride started.

3.pickup_latitude - float for latitude coordinate of where the taxi ride started.

4.dropoff_longitude - float for longitude coordinate of where the taxi ride ended.

5.dropoff_latitude - float for latitude coordinate of where the taxi ride ended.

6.passenger_count- integer indicating the number of passengers in the taxi ride.

# Target-
fare_amount - float dollar amount of the cost of the taxi ride. This value is only in the training set; this is what you are predicting in the test set and it is required in your submission CSV.
