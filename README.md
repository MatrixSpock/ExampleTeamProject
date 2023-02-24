# 507_FinalProject_Team5
# The ELT based United States Airline Flight Status Dashboard Pipeline
## Installation Directions 
1. Download the following datasets: “flights”, “airports”, and “statelatlong”. These datasets can be downloaded from  Kaggle: 
    * Flights & Airports: https://www.kaggle.com/datasets/tylerx/flights-and-airports-data?select=flights.csv
    * statelatlong:  https://www.kaggle.com/datasets/washimahmed/usa-latlong-for-state-abbreviations
2.  In SQL Workbench create a schema titled “us_airlines” and load in the three datasets. 
3. Download the project code from this GitHub repository and run cells. This can be accomplished by cloning the repository onto your device using the commands below: 
    * git init
    * git clone https://github.com/edwardam5/507_FinalProject_Team5.git
## Contributors 
Summer Purschke, Minsu Kim, and Anusia Edward
## Methods Used 
* EDA
* Data visualization
* Data transformation
* Data pipeline
## Technologies 
* MySQL
* Python via Jupyter Notebook
* Visual Studio 
## Project Introduction
The goal of this project is to help air travel passengers access and understand air travel data better by building a data pipeline project to process air travel data. The dashboard pipeline has a total of five different visualizations. The dashboards consist of (1) an interactive table will pull information regarding that particular flight based on a given flight number, (2) an interactive map with various features, (3) a bar chart showing the range of departure times as well as arrival times in terms of how many minutes early or late the flights are per each airplane carrier, (4) an interactive bar chart of the average departure time in minutes by day of the week, and (5) an interactive bar graph depicting the average arrival time in minutes per each day of the week.

## Project Description 
The goal of this project is to build a data pipeline project to process air travel data.
### Data Source + Description 
Data used for this project was retrieved from Kaggle.

Data sets used are:
* flights: day of the month on which the flight was taken, day of the week on which the flight was taken, the flight carrier, airport ID for the departure site, airport ID for the arrival site, the number of minutes a departure was delayed (-63 to 1863), and the number of minutes an arrival was delayed (-94 to 1845)
* airports: airport ID, the city the airport is located in, the state the airport is located in, and the name of the airport
* statelatlong: state abbreviation for the U.S., latitude, longitude, and city
### Background
In the united states, the most popular mode of public transportation for long distance travel is airplanes. As an airline passenger, being able to view flight status is an important component of feeling prepared and secure during travel. To help passengers have access to this information, a dashboard with visualizations was created to help with identifying flight status and making informed decisions when choosing specifics like airline type, departure and arrival location, and day of travel for their flights. 
