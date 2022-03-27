# Stock-Market-Prediction

In this project I choosed a target named Target1 and set it to be the output of the model.

Target1 is defined as if the share experiences 15% of raise before 8% of reduction in price, sets 1 and if not, 0.
In some cases I choose the price of future days as the goal.
The ways I splited data to train and test are:
1. Sequential: first 90% of the data as train_data and last 10% as test_data.
2. Randomized: split data randomly by 70% for train_data and 30% for test_data.
