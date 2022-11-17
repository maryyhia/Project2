
# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing Data and Kaggle Challenge

## Notebooks
- Part 1: Data Cleaning
- Part 2: EDA, Visualisation, Feature Engineering, Feature Selection
- Part 3: Model

## Background
#### Real Sky Estate Development has been developing residential areas around Ames and is looking to procure and develop new housing in the area. 

Previous housing developments were not returning favourable profits due to the recent pandemic and political tensions. It also caused a rise in the costs of living and building materials over the years.

Facing a forecasted recession in the upcoming year, Real Sky senior management team has reached out to our data science team to pinpoint factors that will direct towards revamping the company’s focus structure to improve the attractiveness and sales price of new housing developments.  

## Problem Statement
#### What core features should we, Real Sky, focus on to increase the sale price of homes for our next development project?

## Target Audience
- Non-technical Senior Management of Real Sky Estate Development

## Data Provided
Ames Housing Data
 * ['train.csv'](./datasets/train.csv)
 * ['test.csv'](./datasets/text.csv)
 
 Additional Resources
 * [Ames Housing Data Dictionary](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt)
 
 
 ## Data Dictionary
 |Feature|Type|Description|
 |---|---|---|
 |traindf|Data Frame|Imported Ames Housing Data|
 |trainCat|Data Frame|Categorical Features|
 |trainNum|Data Frame|Numerical Features|
 |replace|Dictionary|Rating values for replacement|
 |replace2|Dictionary|Rating values for replacement|
 |CorrSaleSorted|Data Frame|SalePrice correlation|
 |features|List|List of numerical features|
 |trainNumE|Data Frame|All selected numerical features|
 |catFeatList|List|List of categorical features|
 |trainCatFil|Data Frame|Filtered categorical features|
 |Cat_List|List|List of object type for OneHotEncoding|
 |Cat_train|Data Frame|Object type categorical features for OneHotEncoding|
 |cat_encoded|Data Frame|Categorical features encoded|
 |trainCatE|Data Frame|Categorical featres encoded|
 |train_feat|Data Frame|Combined features|
 |X|Data Frame|All features excluding SalePrice|
 |y|Data Frame|Only SalePrice feature|
 |ss|Object|Instantiated StandardScaler|
 |lr|Object|Instantiated LinearRegression|
 |lasso|Object|Instantiated LassoRegression|
 |ridge|Object|Instantiated RidgeRegression|
 |lr_score|Array|Linear regression score|
 |lasso_score|Array|Lasso regressoin score|
 |ridge_score|Array|Ridge regression score|
 
 ## Summary of analysis
 An overall score of 0.80 using the Lasso Regression model. It has indictated that Overall Qual and Gr Liv Area has the highest coefficient values in contributing to SalePrice. Primary focus and efforts should be channeled into these 2 features to boost overall sales figures. Secondary focus and efforts can be channelled into 1st Flr SF and Bsmt Qual.
 
 ## Conclusions/ Recommendations
 By identifying the key features that would increase sale prices of homes in future developments, actionable steps can be taken. 
 
 Efforts in monitoring new trends in housing market would prove useful. This includes noting changes in home buyers preferences and trends.

Budget allocation in the core features for development and planning in architectural and designing processes. This allows for homes to be built with features attractive to home buyers.

Marketing efforts centred around promoting the key features will ultimately increase in sale of homes and therefore return better profits for the company.
 
 
