# Udacity_blog_post
Write a blog post  Airbnb  data. and data analysis on the Airbnb  data

## Motivation
The analysis is to explore, investigate and explain factors relate to the price and the customer reviews of Airbnb listings.  
## Programming Language
Python

## Packges 
<br>General: numpy, pandas, 
<br>Plotting: matplotlib, seaborn, 
<br>Data clearning: math, re, decimal, datetime
<br>Data Modeling: sklearn

## The analysis follows a CRISP-DM model.

## 1. Business Understanding
<br>Question 1: What factors relate to the price of an Airbnb, in addition to the size of the space? The size of the space is normally defined as square footage, and it is also reflected as in number of bedrooms or number of people accomendates. The size of the space will not be the focus of this analysis.
<br>Question 2: What factors relates to the review ratings of an Airbnb property? 
## 2. Data Understanding
1. Screened all features to understand what is available.  
2. In absent of a codebook, removed features whose names are not self-explanatory.  
## 3. Data preparation
1. Cleaned out missing values depending on the amount of missing and the mechanism behind the missing values.
2. Converted object features to quantitative ones when appropeiate.
3. Engineered new features based on features that are in the data.
## 4. Modeling
Investigation on Price 
Note: the outcome is the logarithmic transformation of the original price feature. The original feature is substaintially skewed to the right, leading to difficulties in applying a linear regression model. 
1. Model 1: Linear Regression Machine Learning Algorithm. (Rsquare = 0.58)
2. Model 2: Gradiant Boosting Machine Learning Algorithm. (Rsquare = 0.65)
Investigation on the overall review rating
Model: Linear Regression Machine Learning Algorithm. (Rsquare = 0.74)
## 5. Evaluation
The model was trained and tested. The MAE, MSE, RMSE and Rsqaure measures are calculated and can be found in the jupyter notebook. 
## 6. Deployment/Explanation
The analysis is conducted to identify answers to the business questions. The models identify the most related features to the price and the review ratings, while accounting for all other features. A blog post has been written to share and explain part of the findings to a non-technical audience. The purpose of the post is to help the audience to save money on Airbnb bookings, when visit the NYC. To visualize the relation between the features and the outcome variables, plots are generated and attached to the post.
