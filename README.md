# Predicting HouseSales of King County USA using Linear and Ridge Regression 
This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. We have performed Linear and Ridge Regression to predict the Housing Sales.

The details of all columns is given below:

**id** : A notation for a house

**date**: Date house was sold

**price**: Price is prediction target

**bedrooms**: Number of bedrooms

**bathrooms**: Number of bathrooms

**sqft_living**: Square footage of the home

**sqft_lot**: Square footage of the lot

**floors** :Total floors (levels) in house

**waterfront** :House which has a view to a waterfront

**view**: Has been viewed

**condition** :How good the condition is overall

**grade**: overall grade given to the housing unit, based on King County grading system

**sqft_above** : Square footage of house apart from basement

**sqft_basement**: Square footage of the basement

**yr_built** : Built Year

**yr_renovated** : Year when house was renovated

**zipcode**: Zip code

**lat**: Latitude coordinate

**long**: Longitude coordinate

**sqft_living15** : Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area

**sqft_lot15** : LotSize area in 2015(implies-- some renovations)

The dataset looks like this

![Image of Dataset](https://hmp.me/dbuu)

We have preprocessed the dataset to impute the missing values and performed data exploration on the processed data to found out the linear corellation between houses having waterfront and their higher price as compare to other houses.

![Image of Dataset](https://hmp.me/dbuv)

We also found out the corellation matrix of other features in this dataset. We have tried out linear and ridge regression to train the model. We have also used Standard Scalar and Polynomail Features for pieplining. The accuracy using Linear regression is 75% wwhile the ridge regression gives 70 %

