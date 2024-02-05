# Local-Adventurer
An emulation based system for distributed file storage and parallel computation.

The main objective of this project is to
1. Build an emulated distributed file system (EDFS) using MySQL.
2. Implement partition-based map and reduce (PMR) on data stored on EDFS for
search/analytics function.
3. Create an app for searching and analyzing the data stored in EDFS using the functions
implemented using PMR.

To perform the project, we need to have enough data, and here we focus on information regarding flights, restaurants in New York, Boston and Seattle .

● Dataset 1 : Flights and Airport Data
This dataset contains all the information of the flights and airports of the USA. The airport dataset has airport_id, city, state and name. And the flight dataset has DayofMonth, DayOfWeek, Carrier, OriginAirportID, DestAirportID, DepDelay, ArrDelay. We perform analysis, cleaning, and remove outliers to get out the necessary data which has the information of the airport and the flights in New York.
Dataset Link : https://www.kaggle.com/datasets/tylerx/flights-and-airports-data

● Dataset 2 : American Fast Food Restaurants
This dataset contains all the information of all fast food restaurants in America. It has columns with ID, Address, city, country, name of restaurant, postal code and province.
Dataset Link : https://www.kaggle.com/datasets/datafiniti/fast-food-restaurants
