## Background
Airbnb allows individual homeowners to rent their properties. With a wide variability of locations and price indicators, hosts often find themselves wondering if the price they offer is considered fair. 

Offering right prices is very crucial for hosts, because Airbnb rental market is competitive. This project analyzed the factors that may have significant roles in affecting prices, which will provide comprehensive insights about Airbnb rental price valuation across the U.S.

## Business Impact
Pricing is one of the most important decisions that hosts need to make to gain profits. 
The prediction exercise here provides a method to predict prices for properties around the same area with similar conditions. 
It will give the hosts a better idea of the property’s market values. 
Airbnb can retain hosts, expand its business, and eventually increase revenues.

## Data
Data is sourced from: https://www.kaggle.com/datasets/kritikseth/us-airbnb-open-data.
Contains 17 columns and 226030 rows. 
Key variables include host id, price, room type, city, and number of reviews.
Gives insights regarding 2020 pricing as per location in the United States. 

## Methodology
Data preprocessing: Drop missing data and remove outliers 

#### EDA: 
Create histograms and correlation matrix for numeric features
Visualize listings and prices distributions across states

#### Data Modeling: 
Use linear regression, XGBoost and multivariate adaptive regression splines  to predict prices
Compare the model performances by RMSE, MAE and R2 Score
