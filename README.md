# Flight-Price-Prediction
This Project is to explore the uses of EDA for tracking flight prices and how to present them

### About this Dataset
Dataset - Flight Price Details from kaggle (https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction?resource=download)

### Introduction:
The objective of the study is to analyse to get meaningful information for the following questions such as.

a) If there are price differences between the airlines.

b) Difference in purchase prices of tickets based on time before depature.

c) If the ticket price changes based on the depature and arrival time of the flight. 

d) Changes in prices based on the duration of the flight.

e) The price difference between Economy and Business class.

### Dataset:
Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

### Features of the dataset:
The various features of the dataset are explained below:

1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.

3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.

4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.

5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.

8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

10) Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.

11) Price: Target variable stores information of the ticket price.
