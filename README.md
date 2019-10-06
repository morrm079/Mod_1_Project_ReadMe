# Mod_1_Project_ReadMe
# King County House Sales Linear Regression
Given sale prices of previous how sales, how accurately can we predict future house sales and which features of the house/property aid in the prediction?
## DataSet 
We were given a dataset of house sale prices for King Country. Along with the sale prices, we were given features of the houses such as the number of bedrooms and bathrooms of the house and other property features. Some of the data did need to be cleaned, as some data was missing for certain sales and some of the features were not in the listed in the correct format. 
## Important Features
By analyzing the data, we were able to see that certain features were more important in determining the sale price of a home than others. One of the most important features being the grade the county gave to the home. It is based on a sale from 1-13, with the 13 being the best score possible.
## Feature Engineering 
I used the data given to creature another feature, price per square foot. I thought this would help determine the value of different areas. Since two houses could have sold for the same price, but they could have very different features, such as location. You can see from the graph that there are some homes that have a higher price per square foot. This could be for different reasons, they could have just been over priced, or they could have had a waterview.
## Modeling
After running an OLS regression with our feature variables, we used feature ranking with recursive feature elimination to see what our top features are. Using the top 9 features we were able to obtain an R squared value of 0.914, this tells us how fitted our data is to the regression line.  

The variables we used to determine this were:
* waterfront
* grade 
* price_per_sqft 
* sqft_living 
* sqft_lot
* bathrooms
* yr_built
* view
* condition
