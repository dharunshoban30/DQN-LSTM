# 🤖 FYP: Stock Trading Using Deep Reinforcement Learning

## Overview
This is my degree Final Year Project during my final year studies in university. This research project explores the application of DRL in stock trading, particularly the optimization of trading strategies. In other words, it is a trading bot that autonomously makes trades based on past experiences and trial-and-error. The scope of this research consists of historical stock data of three NASDAQ companies: Amazon, Google, and Microsoft spanning 10 years. The DRL model chosen for this research project is Deep Q-Networks with Long Short-Term Memory neural network architecture. The model achieved a CR of 82.73%, SR of 0.93, and a MDD of -24.15%. This research not only contributes to the optimization of stock trading strategies through DRL, but also provides a structured model for addressing the complexities of financial markets.

## Objectives
The primary objectives of this project are to:
- To improve the performance of stock trading models by applying feature engineering techniques to obtain technical indicators used by DRL models.
- To improve the performance of stock trading models by using DRL during normal stock market conditions in simulated trading environments withperformance
  metrics such as Cumulative Return (CR) and Sharpe Ratio (SR).
- To improve the performance of stock trading models by using DRL during bearish and volatile stock market conditionsin simulated trading environment with
  Maximum Drawdown (MDD) as a performance metric.
  
### File Descriptions:
**1. First_Notebook.ipynb**
- This file contains the code I used to clean the datasets and perform EDA, Feature Engineering, Feature Selection etc.

**2. Second_Notebook.ipynb**
- This file contains the code for Model Training, Hyperparameter Optimization, and Results Analysis.

**3. AMZN.csv, GOOGL.csv, MSFT.csv**
- These raw stock datasets are obtained from Yahoo! Finance to be loaded into the first notebook. 

**4. Stock Trading using Deep Reinforcement Learning.pdf**
- The pdf file contains the completed journal paper used for submission. 

## Instructions
To execute the notebook, follow these steps:

1. **Setup Environment**:
    - Ensure you have Python and Jupyter Notebook installed.
    - Install necessary libraries using the following commands:
      ```bash
      pip install numpy pandas matplotlib scikit-learn
      ```

2. **Download the Datasets**:
    - Ensure the datasets is available in the same directory as the notebook.

3. **Running the Notebook**:
    - Open the Jupyter Notebook and navigate to the `First_Notebook.ipynb` file.
    - Run all cells sequentially to see the complete workflow and results.
    - Do the same for `Second_Notebook.ipynb` after finishing the first notebook.
  
## References
- Datasets: [Yahoo! Finance](https://finance.yahoo.com/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAAIpvVmT2OYBkokMJPv8aK1cuy6TK7hs5Yq2321MOPNSj6uOpLhellHY6OPQzRgyXEvttsHqhI1_ntA4LDu-0ZyhUby6NE_3XnHfa50H40zGrq23XC4eIgcaQRmee_dXEvotCf2x9DcECo_Q6yRhl7MGdWw0yrvY2O4SsLa5lPUQr)
