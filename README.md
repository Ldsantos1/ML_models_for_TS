﻿## ML_models_for_TS

#### This is simulation using 2 different time series. Each data source contain about 396 observations and 

#### are in two different files: random_walk.csv and trend_season.csv. Each one simulating a different pattern on demand. 

### For the random walk dataset:

#### The best prediction for Yt+1 in a random walk dataset is: Yt+1 = Yt + error. Given that this error (iid noises) are

#### are normally distributed. In the example, the errors have N(0,1). In essence, the model should propose the following 

#### estimation: Yt+1 = Yt. Chosen models for this dataset: Random Forest, XGBoost and SARIMA.

### For the trend and seasonal dataset:

#### The models should capture both patterns. In this case I just considered XGBoost and SARIMA. In both cases the MAE were very low.


