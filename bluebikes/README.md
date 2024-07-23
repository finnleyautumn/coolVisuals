# Blue Bikes Visualizations
*Finnley Autumn Rogers* | 2024-07-22

Data Source: [Kaggle Link](https://www.kaggle.com/datasets/jackdaoud/bluebikes-in-boston)

## Goal
I am not planning to create a complete analysis using this data, rather I would like to use it as a platform for experimenting with new visualization techniques and honing my existing skills. You do have to posess some level of curiosity to create interesting visuals so some analysis will be done as a byproduct, but I wanted to state from the outset that I'm just here to make some cool stuff.

## Data Overview
Boston BlueBikes is a publically owned bike sharing program operating in Boston, Brookline, Cambridge, Everett, and Somerville. Initially established in 2011, the program has grown to include 13 municipalities and has seen users log over 22 million rides. [source](https://www.boston.gov/departments/transportation/bluebikes#about-our-system) 

I have a personal connection to the program as I personally have been nearly run over by riders on numerous occasions and even once tripped over a blue bike left in the middle of the sidewalk for some reason. (source: you're just going to have to trust me on this)

Raw data contains 2 csv files;

 - `bluebikes_tripdata_2019.csv` (2.52 million rides)
 - `bluebikes_tripdata_2020.csv` (2 million rides)

with the following variables:

- `tripduration`: duration of trip in seconds
- `starttime`: start time and date of trip
- `stoptime`: stop time and date of trip
- `start station id`: unique ID of station the trip started at
- `start station name`: name of station the trip started at
- `start station latitude`: latitude of start station of trip
- `start station longitude`: longitude of start station of trip
- `end station id`: unique ID of station the trip started at
- `end station name`: name of station the trip ended at
- `end station latitude`: latitude of end station of trip
- `end station longitude`: longitude of end station of trip
- `bikeid`: unique ID of bike used for trip
- `usertype`: type of user can be Customer or Subscriber
- `postalcode`: postal code of user
- `year`: year of when the trip took place
- `month`: month of when the trip took place
- `birth year`: birth year of user
- `gender`: gender of user

Ok cool lets make some stuff
