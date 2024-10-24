# Flight-Price-Prediction

## Dataset
The data is taken from: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

<u>Objective</u>
-------------

The aim of this project is to predict Target or dependent variable, Ticket price based on the independent variables :-
>* Airline (airline)
>* Source and destination (source_city , destination_city)
>* Time of departure and arrival (departure_time , arrival_time)
>* Seat type (class)
>* Number days before days before the travel (days_left)
>

<h1 align="center"  style=" color:#fff; background-color:#969696; padding:10px;">Data understanding </h1>


Dataset contains information about flight booking options between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset. .

## <u>Features</u>
The various features of the dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

3) Source City: The City from which the flight takes off. It is a categorical feature having 6 unique cities.

4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

7) Destination City: The City where the flight will land. It is a categorical feature having 6 unique cities.

8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

10) Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

11) Price: Target variable stores information of the ticket price.
