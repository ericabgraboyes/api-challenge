# python-api-challenge

### Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

* Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude -- graphs to plot are listed below
** Latitude vs. Temperature
** Latitude vs. Humidity
** Latitude vs. Cloudiness
** Latitude vs. Wind Speed

* Requirement 2: Compute Linear Regression for Each Relationship -- comparing variables for Northern and Southern Hemispheres
** Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
** create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values

#### the linear regressions should reflect that data captured in the scatter plot -- with graphs for northern vs. southern hemisphere

### Part 2: VacactionPy
In this deliverable, you'll use your weather data skills to plan future vacations - using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather conditions

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
* For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
* Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:
