# Real_Tech_Influence
Visualizing various business types around major coorporations and tech headquarters. Specifically focusing on McDonald's (West Loop), Groupon (Cabrini Green) and Coyote Logistics (Logan Square/Bucktown). The adjacent business types include "Special Event Beer and Wine", "Retail Sales of General Merchandise", and "Fitness Classes". We wanted to see if there are any variations of adjacent business around these three main companies. 

## Extract
Based on the three businesses of interest, we extract data from eight zipcodes from The City of Chicago Data Portal for business licenses via API calls for each zipcode using. Python libraries: pandas, requests, and json.

## Transform
Then we select certain information from the business licenses to include in new data frame.

## Load
We use MySQL to load the data. Pythong: sqlalchemy

## Visualize
We create a website to show the relationship between the three companies and the adjacent businesses using a map that allows a user to select the types of adjacent businesses on the map. Html: bootstrap, css, JS: leaflet, d3


