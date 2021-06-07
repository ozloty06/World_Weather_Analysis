# World_Weather_Analysis

## Project Overview
PlanMyTrip specializes in internet related services for the hotel and lodging industry. Their user interface team is developing software to filter by customers' preferred travel criteria to help them identify ideal travel destinations for their temperature preferences. As part of the development of the new PlanMyTrip app, Beta testers have requested adding weather descriptions to the weather data the app retrieves and asked to provide input on temperature preferences to help identify potential travel destinations and nearby hotels. 

## Resources
- Data Source:
- Software: Python v.3.8.5
- Jupyter Notebook 6.1.4 with Pandas, Matplotlib and Numpy
- APIs
  - CitiPy
  - OpenWeather API
  - Google Maps Platform (including Places API and Directions API)

Note: 
statistical analysis and linear regression was performed on weather parameters in northern and southern hemispheres as part of this analysis.

## Summary
In this deliverable we generated 2000 random latitudes and longitudes to retrieve the nearest city and perform and API call to retrieve weather data for the cities. Next we retrieved customer weather preferences using input statements and identified potential travel destinations and nearby hotels. These were plotted on a world map with pop-up markers displaying location and weather data. Finally, we used the Google Directions API to create a travel itinerary to show the route between our selected cities and created a layer map with pop-up markers for each city and a route map between our selected cities.
