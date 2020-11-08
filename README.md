# NewYork-Taxi-Demand-Prediction
Objective:
To predict the current taxi fare based on previous lags fares

Approach:

1.Univariate analysis is done and the outliers are removed from data

2.We used t-5 pickups to predict the next pickup and we have added 3 more features to the data

3.They are single exp-avg,triple exp-avg and fast fourier transform feature

4.And 3 different algorithms(LR,Random forest,Xgboost) are applied on the data

5.Xgboost performed really well of all the algorithms giving us very good test mape of 0.0973
