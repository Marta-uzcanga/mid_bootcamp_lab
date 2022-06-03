# mid_bootcamp_project

The project focuses on analising data obtained from Kagle about wine. The data set is very extensive and had to be cleaned from redundant information and null values. 
Some values also had to be converted. 
At first glance, the information is very varied as it provides information about geographical origin of the wine, price, type, usage, flavour profile etc. 
Even though it is all interesting, at first, it is unclear whether it will all be useful for the ultimate goal which is to create a prediction mdoel that predicts the type of wine (red, white, rosé or sparkling). 
In the first few steps I have aggregated and grouped information to get a general idea of the data and how it is related, these are also shown in the presentation through graphs. 
The next step is to use chi2 test to determine if the categorical columns have a relationship, in this case, all seemed to be related. 
There is also a two sample t-test done to determine if the avergae price of the different types of wine has the same distribution. The result of this is also that they are indeed the same. 
This result seemed seem to show a different story but it seems to be due to class imbalance. 
The prediction model is done using the logistic regression model. On the first trye the accuracy and kappa scores show that it is a great model but the confussion matrix clarifies it does a great job p
This also stems from the class imbalance in the data set, to fix this I apply weight balance to the model and the results improve significantly. 

Learnings and nest steps: 
For the next steps I would like to develope a wine recommender, but would also like to include natural language processing to be able to use wine review data. 
I feel like the flavour profile data in the data setis very usefull but not specific enough for a recommender. I would also like to obtain new data to be able to somewhat improve the class imbalance in teh data set. 
However, I believe the class imblanace is not as big of a problem as it seems because it is proporcionally related to the total production of types of wine worldwide. 
The country of origin however, is not representative of the world wide wine production by country. I will also aim to fix this in the next project.