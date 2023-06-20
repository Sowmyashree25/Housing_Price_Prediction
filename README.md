# Housing_Price_Prediction
**Problem Statement**
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.



**Business Goal**
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


**General Information**
In this assignment, we will use a hybrid combination of RFE and manual menthods for feature selection.
   build a linear regression model with ridge and lasso regularization for predicting 'SalePrice', which is the final selling price of a property.
   Find optimal regularization parameters for each of the methods using Grid search with K-Fold cross validation.
   Use R-squared score on the test set to evaluate our model
   Decide which model to go with.
Note that our main criterion of selecting a model would be 
   scores, especially on testing data. Further consideration will be given to Lasso if it successfully selects fewer variables in the model.

**Conclusions**
The most important features to determine the price of a property are:

   Among the two regression model, we can choose lasso regression model, because it has good R2 value for test set. And also lasso regression has low RMSE value compared to ridge regression. And apart from 
   that the lasso regression helps in feature elimination which cannot be performed by ridge regression.

. OverallQual_Other (Coefficient: 0.917)
• OverallQual_8 (Coefficient: 0.485)
• TotalBsmtSF (Coefficient: 0.242)
• SaleCondition_Partial (Coefficient: 0.263)
• Neighborhood_Crawfor (Coefficient: 0.394)
    
    
  
**Technologies Used**
numpy - 1.23.1
pandas - 1.4.3
sweetviz - 1.2.0



**Contact**
Created by [@Sowmyashree.br - feel free to contact me!
