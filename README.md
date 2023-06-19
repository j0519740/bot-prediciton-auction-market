# bot-prediciton-auction-market
The objective of this project is to understand the problems posed by malicious bots on the auction market leading to impact on business profitability and customer dissatisfaction. We propose to design a model with the help of data analysis and machine learning to identify and eliminate such bots with the aid of Bot Prediction Lifecycle. Finally, we intend to show the business application using Expected Value framework to test for deployment capability.


## Bot Prediction Lifecycle
![image](https://github.com/j0519740/bot-prediciton-auction-market/assets/99134168/96e0856b-7d80-4202-9ff8-be0f59a33960)
### General workflow of business analytics approach applied to current study
Based on the background and objective of the use case, the following Bot Prediction Lifecycle is proposed to help solve the problem statement. The steps of this lifecycle are aligned with the business analytics lifecycle.
1. Business Understanding: Understanding the impact of bot sniping on auctions and the need to eliminate them. The desired outcome is to retain the genuine customers from leaving the platform due to dissatisfaction (as they are unable to win bids)
2. Data Acquisition: Collecting data on bidder (describing whether it is a bot or a human) and the bids of various auctions (describing how, what and when of a bid)
3. Data Preparation: Merging different datasets, engineering the features to create more useful features for better predictability. Plotting the density functions to understand the importance of different features.
4. Modelling: Designing the cost-benefit matrix based on business understanding and the profitability of the prediction. Implementing the machine learning models for training and testing the data.
5. Evaluation: Comparing the performance metrics like accuracy, precision, recall, f1 and Expected value of all models. Identifying the best performing model.
6. Deployment: Comparing against the scenario where there is no model to predict the bots, using Expected value framework to check whether the model is ready for deployment.
Figure 1: Bot Prediction Lifecycle
However, as shown in the figure above, this lifecycle is an iterative process. As more data is collected and business understanding is updated based on business metrics such as customer base retention and revenue loss due to bots, the model will be trained and updated and deployed in a periodic manner to identify bots from human bidders.

The study done to identify the best model to use for the bot prediction lifecyle and the Expected value framework is further detaulied in the report in this Repo.
