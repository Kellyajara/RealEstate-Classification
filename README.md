# Housing Price Analysis in Kings County, Washington
![image](https://github.com/Kellyajara/Phase2_Project/assets/131709766/725176b5-b09f-4b5a-b68a-e9e6d5c85b76)

By: Kelly Jara, Bianna Gas, Laibah Ashfaq

## Overview
This project utilizes King County housing data from 2014-2015 in order to make predictions regarding the sale prices of houses based on certain home features. After our exploratory data analysis and multiple linear regression modeling, we have determined that location, waterfront, house grade and square footage have the largest impact on increasing the sales prices of homes in this region.

## Business Problem
Our stakeholder, The Corcoran Group is looking to expand into the Kings County area housing market to grow their west coast footprint. In order to help them get to know the real estate market in this new area, we were tasked with analyzing what home features help increase the sales price of the properties. Using our data, the real estate company can narrow down which homes to focus on that would command a higher sales price. 

## Data
This project utilize a dataset from Kaggle regaridng Kings County, Washington home sales between 2014-2015. The source includes certain home features such as: 
  -Bedrooms: Number of bedrooms
  -Bathrooms: Number of bathrooms
  -Sqft Living: Square footage of living space in the home
  -Sqft Lot: Square footage of the lot
  -Floors: Number of floors (levels) in the home
  -Waterfront: Whether the house is on a waterfront
  -Greenbelt: Whether the house is adjacent to a greenbelt
  -Nusiance: Whether the house has traffic noise or other recorded nuisances
  -View: Quality of view from house
  -Condition: How good the overall condition of the house is. Related to maintenance and age of the house.
  -Grade: Overall grade of the house. Related to the construction and design of the house.
  -Heat Source: Heat source for the home
  -Sewer System: Sewer system for the house
 
## Modeling
After cleaning our data, we performed a 70%-30% Train-Test split on the data with price as our target variable and all other variables as predictors. Afterwards, we created multiple iterative linear regression models.


## Recommendations
Our recommendations for prioritizing realtor efforts are as follows:
  - Homes in specific zipcodes (98039,98004,98040,98033,98112)
  - Homes on the waterfront
  - Homes with the highest home grade possible 
  - Larger sqft homes

Other features that helped increase sales price significantly include view, condition, bathrooms and greenbelt. 



  

