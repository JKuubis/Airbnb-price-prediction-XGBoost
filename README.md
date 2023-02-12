# Executive summary

Setting the right price for an Airbnb rental property is important, especially in large cities like Barcelona, where exists strong competition. Setting a price that is too high can cause rental difficulties. On the other hand, a price that is too low will result in a loss of the potential income that could be earned from renting the property.

Currently, Airbnb platform offers some support in this regard by showing the average price of rentals in the nearest area, taking into account the number of available beds in a given accommodation facility. However, it ignores many other factors that can have a significant impact on determining an appropriate price, such as: available amenities, number of bathrooms, type of accommodation, distance from the city center or score of ratings given by guests. The aim of this project was building XGBoost model to make predictions on rental prices of accommodation facilities in Barcelona listed on Airbnb portal. With the use of such model, it could be created a tool to assist hosts in determining an appropriate rental price, as well as showing how the price could change after making certain changes, such as adding or removing a particular amenity to/from the property. On the other hand, it could also be useful for those tourists interested in renting to determine whether a particular accommodation is worth its price. Model concentrated on tourist-oriented accommodation facilities, i.e. those that were available for short-term rental (less than 30 days).

In the first part of the report dataset used in the project was described. Later, data cleaning and transformations were performed, and some new variables were added. Next, hyperparameters tuning for XGBoost model was performed in order to choose final model which was later evaluated based on error metric. Also, relative feature importance was calculated and partial dependence plots for continous variables were created.

# Dataset

Data used in this project comes from insideairbnb.com.

# Technologies used

Project was prepared in Python using below libraries:

* pandas
* 
