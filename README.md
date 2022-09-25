# Project 2: Predicting House Prices in Ames, IA

### Problem Statement/Objectives

1. Find the key features that influence the sale price 
2. Develop and evaluate models to predict the house price in Ames, Iowa by using multiple linear regression



### Data Dictionary

The features developed through feature engieering process are the following

|Feature|Type|Dataset|Description|
|:--------|:------|:---------|:-------------|
|total_sqrft|float|Ames_train|total house area including basement| 
|total_sqrft_abgr|float|Ames_train| total house area  excluding basement| 
|area_per_room|float|Ames_train|area per room| 
|total_bathroom|float|Ames_train| total number of bathroom | 
|overall_impact|float|Ames_train|overall impact using interaction between Overall Qual' and  'Gr Liv Area'| 
|overall_garage|float|Ames_train|overall impact of garage using interaction between 'Garage Cars and  'Garage Area'| 

The original data descriptions can be found at this link https://github.com/niphonch/DSI_Project2_Ames_House_prediction/commit/6f799f8dcf515f2c9e1edf65f59248e717f3b832

### Analysis

1. Import data and data preprocessing
    * Data cleaning
    * Dropping irrelevant coulumns
    * Removing and imputing null values
    * Removing outliers
    * Data engineering 
    * Log transforming dependent variable (SalePrice)
2. Exploring and transform target vaiable (SalePrice)
3. Feature selection: Numerical and Categorical variables
4. Using LASSO to explore potentail catergorical features
5. Model building


### Conclusion and recommendation

  The aims of this study is to find the key features that influence the sale price and develop models to predict the house price in Ames, Iowa by using multiple linear regression. 
      The results suggests that these features are good predictors of house price
      1. Total house area
      2. Overall quality
      3. Garage cars
      4. Total bathroom
      5. Area per room
      6. Total room
      7. Fireplaces
      8. Age of house
      9. Age after remodeling
      10. Kitchen quality
      11. Exterior quality
      12. Neighborhood

   Based on our results, we reccommend that 
    1. If you are considering a home purchase or investment in Ames, you can use this model to find an appropriate house by efficiently predicting housing prices in the Ames market.
    2. If instead selling a home in Ames, given the significance of some features in predicting house prices there, you can invest in upgrading those features to improve their sale price.


