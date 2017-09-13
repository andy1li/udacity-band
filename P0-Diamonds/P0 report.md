## Project: Diamond Prices

### Step 1: Understanding the Model 

- According to the linear model provided, if a diamond is 1 carat heavier than another with the same cut and clarity, how much more should we expect to pay? Why?


We, if we were retail customers, should expect to pay 8,413 dollars more for every 1 carat of increase in weight. With all other factors controlled, the linear regression model


**Price** = -5,269 + 8,413 x **Carat** + 158.1 x **Cut** + 454 x **Clarity**

just becomes:

**Price** = 8,413 x **Carat** + **AllOtherFactors**

- If you were interested in a 1.5 carat diamond with a Very Good cut (represented by a 3 in the model) and a VS2 clarity rating (represented by a 5 in the model), how much would the model predict you should pay for it?


**Price** = -5,269 + 8,413 x **Carat** + 158.1 x **Cut** + 454 x **Clarity**

​          = -5,269 + 8,413 x 1.5 + 158.1 x 3 + 454 x 5

​          = 10094.8


### Step 2: Visualize the Data 

![diamond_prices](diamond-data/diamond_prices.png)

Good thing about the model is that it captures the general trend of the prices. However, it seems that the predicted range is rather limited and there are negative predicted prices. If these two areas could be improved upon, I might feel more confident in the model.

### Step 3: Make a Recommendation

- I would recommend a total price of no more than $8,128,209, which was calculated with a 70% discount on the predicted sum of prices derived from the above linear model. Since the diamond distributor has decided to exit the market in full, we might get a better discount than the usual 70% by acquiring all its inventory at once.