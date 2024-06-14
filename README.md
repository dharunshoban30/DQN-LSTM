# DQN-LSTM

**1. Code Requirements**

I've included the main requirements of the project for your perusal. It contains everything that is needed for the code in the second file. It also contains the formulas for the performance metrics. 

**2. Code_First-Copy**

This file does not need any changes or modifications. It contains the code I used to clean the datasets and perform EDA, Feature Engineering, Feature Selection etc. I did Standard Scaling initially but found that the results would only output every metric result without it, so decided to just comment that cell for now. With Scaling the Sharpe ratio results just produced 'NaN'.

**3. Code_Model**

This file is where the model is built and trained, along with the environment.
The reason why i only use 5 episodes is because it takes too long to run (3-4 hours). My laptop specs are minimal so I cant really run more episodes.

I am using an initial portfolio value of '100$'.I am not sure what the problem is, but this is the output produced after running:
![image](https://github.com/dharunshoban30/DQN-LSTM/assets/136322910/f9527b19-d16e-4f4f-8596-a8c8ea9e1828)


