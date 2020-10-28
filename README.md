# XoX Sales Analysis and Prediction
**Problem statement**
<br>Historical sales data of product XoX has been provided. The product is featured by numerical informations as cost, weight, height, depth and categorical informations as maker, ingredient, product type and product level. All these features and sales history are known to affect future purchase price, but it's challenging to figure out which features are more inportant in predicting a future pruchase

**Feature processing**
<br>Categorical features would be converted to numerical by dummy (one hot) or ordinal (label encoder) transformation
<br>Numerical features would be scaled if necessary (when not tree based model)

**Machine learning**
<br>1, Predict product price (target) for a future pruchase based on given informations (features) by applying regression models
<br>2, Choose the best model (model performance) and interpret the predicted price (feature importance)

**Metrics**
<br>Model performance can be evaluated in different ways, here R2 score is used
<br>![image-2.png](attachment:image-2.png)
<br>R2 score: the proportion of the variance in the dependent variable (target) that is predictable from the independent variables (features). R2 score is no greater than 1 and the higher R2 the better model performance. A negative R2 score suggests that the model performance is worse than mean value prediction, and R2 score of 1 indicates a perfect prediction.
