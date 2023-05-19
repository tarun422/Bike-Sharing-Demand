# Bike-Sharing-Demand

![177841865-7d86b86b-2849-4240-92c5-26ee85b8715b](https://github.com/tarun422/Bike-Sharing-Demand/assets/81609862/495f39df-4f3f-4dad-aaee-7d1d54545504)


**Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.**


Explore and analyze the data to discover important factors that govern the bookings.

# Dataset Information:-
* Number of instances: 8760
* Number of attributes: 14


# Features information:-

* **Date** : year-month-day
* **Rented Bike count** - Count of bikes rented at each hour
* **Hour** - Hour of he day
* **Temperature** -Temperature in Celsius
* **Humidity** - %
* **Windspeed** - m/s
* **Visibility** - 10m
* **Dew point temperature** - Celsius
* **Solar radiation** - MJ/m2
* **Rainfall** - mm
* **Snowfall** - cm
* **Seasons** - Winter, Spring, Summer, Autumn
* **Holiday** - Holiday/No holiday
* **Functional Day** - NoFunc(Non Functional Hours), Fun(Functional hours)

# Prerequisites
* Understanding of Python and its libraries like Numpy, pandas, Matplotlib and seaborn

# Technologies used
* IDE - Google Colab

**Goal: The main objective is to discover important factors that analyzed bike sharing demand.**

# Project Work flow
1. Importing Libraries

2. Loading the Dataset

3. Data Cleaning

4. Handling Outliers

5. Data Visualization

6. Conclusion

# Conclusion
* Linear Regression, Lasso Regression, Ridge Regression, Elastic Net Regression performance is almost same on both training data and test data which is likely 60% but this is not sufficient

* Decision Tree performance is around 90% on training data and 85% on test data in both case before tuning and after tuning

* Xtreme Gradient Boosting performane is good but the test accuracy is not much as compare to Random Forest

* Random Forest performance is very good on training data that means it tends to overfit on training data but also his test accuracy is very good which is highest in all comperision. But after tuning the hyperparameter its performace goes down

* Default Values of Random Forest algorithm is performing very good with 98% accuracy on training data and 91% accuracy on test data So i choose Random Forest for this dataset
