# multiple_regression-project
# 

# BUSINESS PROBLEM
### Rirko LTD has decided to venture in to the field of real estate constultancy that will help  buyers to get houses  and sellers to get the right price for their houses,as a data scientist I have been tasked to come up with insights that will assist the firm know the best prices based on different aspects or characteristics of the houses available.In order to come up with clear insights that will have impact ,I will apply my analysis based on EDA,Linear regression and Multiole regression modeling.I came up with the following questions to help  guide me during my analysis.The aim of this project is to develop a multiple regression model than can predict a house's price 
 ### which variable/aspect has the highest  impacct on price?
 ### which other variables impact our prices?
 ### which model gives the highest variation/accuracy that will help us predict prices in the future?
 DATA UNDERSTANDING
## The King County Housing Data Set contains information about the size, location, condition, and other features of houses in King County. A full description of the dataset's columns can be found below.

- Column Names and descriptions for King County Data Set
- id - unique identified for a house
- dateDate - house was sold
-  pricePrice - is prediction target
- bedroomsNumber - of Bedrooms/House
- bathroomsNumber - of bathrooms/bedrooms
- sqft_livingsquare - footage of the home
- sqft_lotsquare - footage of the lot
- floorsTotal - floors (levels) in house
- waterfront - House which has a view to a waterfront
- view - Has been viewed
- condition - How good the condition is ( Overall )
- grade - overall grade given to the housing unit, based on King County grading system
-  sqft_above - square footage of house apart from basement
- sqft_basement - square footage of the basement
- yr_built - Built Year
- yr_renovated - Year when house was renovated
- zipcode - zip
- lat - Latitude coordinate
- long - Longitude coordinate
- sqft_living15 - The square footage of interior housing living space for the nearest 15 neighbors
-  sqft_lot15 - The square footage of the land lots of the nearest 15 neighbors

# Interpreting our models

### which variable/aspect has the highest  impacct on price?
 -  grade has a high impact on price because it is mostly correlated with price

 ### which other variables impact our prices?
 - sqft_living,sqft_living15,lat and bathrooms are among other variables  that influences our prices 
 ### which model gives the highest variation/accuracy that will help us predict prices in the future?
 MODEL4 gives because  Grade, sqft_living,,latitude,floors,condition  and bathrooms are the best fit for a multiple regression model. These features are highly correlated with price, have relatively low multicollinearity, and can together account for more than half of the variability of price. All multiple regression assumptions are satisfied with these features include
 ## CONCLUSION
We can see that the house grade is one of the main features that is affecting price,so buyers and sellers should expect a high price for quality houses based on grade and houses with low grade have low value .
Sqft _living,lattitude and bathrooms also have a postive impact on our price,it seems houses with big sqft_living and bathrooms increases the prices.
condition also affects our price in both positive and negative,when the condition is poor and fair the price of the houses reduces but when the house  condition is good and very_good  the price is high.
Our model has some limitations due to removal of outliers and tranforming some of our prices,hence it may not be accurate in different.
Further analysis concerning the housing sector in kings county needs to be done to bring more clarity on the prices of our houses
