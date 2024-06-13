# DQN-LSTM

**1. Code Requirements**

I've included the main requirements of the project for your perusal. It contains everything that is needed for the code in the second file. It also contains the formulas for the performance metrics. 

**2. Code_First-Copy**

This file does not need any changes or modifications. It contains the code I used to clean the datasets and perform EDA, Feature Engineering, Feature Selection etc. I did Standard Scaling initially but found that the results would only output every metric result without it, so decided to just comment that cell for now. With Scaling the Sharpe ratio results just produced 'NaN'.

**3. Code_Second-Colab**

This file is where the model is built and trained, along with the environment.


I suspect the problem might be with the way the performance metrics are written especially Cumulative Return and Sharpe Ratio, but I am not really sure. I think the metrics are not evaluating based on the model itself, but on the prices in the datasets. It might also be the way the model is trained or environment is built. 

The reason why i only use 5 episodes is because it takes too long to run (3-4 hours). My laptop specs are minimal so I cant really run more episodes.
