# Check-In November 13, 2023 Overview

We are going to base the best neighborhood in Pittsburgh by 3 main factors: Air Quality Index, Social Services, and the Census. Here's how we are going to weigh our data to make a decision:
* Air Quality Index data will average out the amount of "bad" air quality index values versus total amount of air quality index values. This will weigh 10 points. We believe this is crucial because the last thing someone wants is to live in a neighborhood where they struggle to breathe. The best-case is the lowest percentage; to collect data for each neighborhood, we will do 1 - bad AQI / total AQI. In theory, the highest number will be the neighborhood with the least "bad" AQI's (on average).  
* Social Events data will average the amount of Social Service Events across several nieghboorhoods in the City of Pittsburgh by the total amount of Events in the area. This will weigh 3 points Social Events help boost interaction with in the community. The best case scenario would be a high average. 
* Census data will average out the amount of people in a particular neighborhood versus total population throughout the City of Pittsburgh (302777). This will weigh 5 points. We believe this matters because we love people and we want to be surrounded by people 24/7/365 because we are crazy. The best-case is the highest percentage.  

The way we will compare the data is take the data of AQI, Social Services, and Census data and weigh them by multiplying their percentages by their weight. We will then add them together and divide by 3 to get a "final" number, which will be our rank. Whichever neighborhood has the highest rank will be the best!

Currently, we must put this data into code and analyze it, as we haven't done that yet. We have decided which data we use and how we are going to weigh it, so consider the "psuedocode" to be done. Once complete, there will be a chart/graph that will display the best neighborhood using our 3 statistics!
