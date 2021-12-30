# Flight_Fare_Predcition
To Predict the prizes of flights using regression.
 - Dataset can be found [here](https://www.kaggle.com/geminikeggler/flight-fare-prediction-reression-analysis/data)

Features:

* Airline: The name of the airline.
* Date_of_Journey: The date of the journey.
* Source: The source from which the service begins.
* Destination: The destination where the service ends.
* Route: The route taken by the flight to reach the destination.
* Dep_Time: The time when the journey starts from the source.
* Arrival_Time: Time of arrival at the destination.
* Duration: Total duration of the flight.
* Total_Stops: Total stops between the source and destination.
* Additional_Info: Additional information about the flight.
* Price: The price of the ticket.

## Cleaning the Data
* Made Columns for Day and Month out of Date of Journey.
* Made Columns for dep_hr, dep_min, Arrival_hr & Arrival_min out of Dep_Time and Arrival_Time respectively.
* Calculated the total flight duration.
* Removed the outliers.

## Mdoel Building
First, I transformed the categorical variables into dummy variables. I tried different models and evaluated them using Root Mean Squared Error.

Different models I tried :
 1. LinearRegression
 2. DecisionTreeRegressor 
 3. RandomForestRegressor 
