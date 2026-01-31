# Bike_Sharing_Demand
Description: An end-to-end regression framework developed to forecast hourly bike rental demand. This project focuses on identifying key environmental and temporal drivers of bike usage.

### Technical Highlights:


**Feature Engineering:** Expanded the dataset to 32 features through One-Hot Encoding and categorical mapping of seasons and weather conditions.


**Data Scaling:** Applied MinMaxScaler to normalize numerical predictors within a 70/30 Training-Test split.


**Feature Selection:** Utilized Recursive Feature Elimination (RFE) to select the 15 most significant features, identifying a high correlation between temperature and user demand.


**Statistical Performance:** Achieved an R-squared score of 0.853 using Ordinary Least Squares (OLS) regression.


**Validation:** Monitored VIF (Variance Inflation Factor) to handle multicollinearity among environmental variables
