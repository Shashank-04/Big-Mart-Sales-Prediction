# Big-Mart-Sales-Prediction

## Introduction:-
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined.

## Objective 
To build a prediction model which can help in increasing sales of BIGMART stores

## Framing our machine learning system -
•	Supervised learning - Since ,we have labelled training data.

•	Regression  - we are supposed to predict the sales price(numerical label).

•	Plain batch learning -Since , the data we have is not changing continuously(cumulative data).

## Selection of Performance Measure –
### •	RMSE
### •	Cross-validation Score

# Assumptions:-
### 1.	Store Level Hypotheses:
o	Sales will get affected due to location of the store , density of population around it, store capacity, competitors ,marketing strategies, customer behaviour and ambiance the store offers.
  
### 2.	Product Level Hypotheses:
•	Sales also gets affected with the kind of brands the store has, packaging of the product, availability of utility products, Display Area which can catch attention and product visibility in the store.

•	Also, Advertisement and attractive promotions catches the eye of a customer.
  
Based on above conditions , we will assume higher values of these conditions will result in more of sales and vice versa.

## Steps followed -
•	We began by eliminating the null values.

•	We then checked the correlation between all the features.

•	Then we explored more about the Outlet type, location of the outlet ,their sizes and sales.

•	Also, about the item types and fat contents in them through variety of EDA plots.

•	We then converted categorical variables into numerical ones using One Hot Encoding in Data Pre-Processing Steps.

•	As, In One hot encoding, each category of a categorical variable is converted into a new binary column (which is 0 or 1).

•	Before deciding on regression models, we checked the statistical inferences ,we are comparing the independent and dependent variables and check the R square value in order to see the accuracy, followed by heat map correlation.

•	In the final steps we applied various Machine Learning models: Linear Regression, Decision Tree, Random Forest & XGBoost.


## Result for Performance Metrices
### •	The RMSE score for XGBoost was observed to be of 1033.
### •	Also, cross-validation scores observed was 58.31%
