# Equatorial_Weather_Analysis_and_Vacation_Planning

Part 1: WeatherPy

Introduction
In Part 1, the analysis focuses on weather data for over 500 cities. The OpenWeatherMap API is used to collect weather information, generate scatter plots to visualize the relationships between latitude and various weather variables, and compute linear regressions to gain insights into how weather patterns change across different hemispheres.

Requirements
1. Data Retrieval: The project starts by using the OpenWeatherMap API to retrieve weather data for more than 500 cities, each located at varying distances from the equator.

2. Data Visualization: Visual exploration includes creating scatter plots for the following relationships:
    * Latitude vs. Temperature
    * Latitude vs. Humidity
    * Latitude vs. Cloudiness
    * Latitude vs. Wind Speed
    
3. Linear Regression Analysis: Further analysis involves computing linear regressions for each of these relationships. The analysis is performed separately for the Northern and Southern Hemispheres to identify patterns.

Usage
1. Jupyter Notebook: Open the provided WeatherPy.ipynb Jupyter notebook. This notebook serves as the guide through the analysis and visualization process.

2. Execution: Run the notebook to generate the required plots and conduct an in-depth analysis of the relationships between weather variables and latitude.

Results
Upon completing Part 1, a deeper understanding is gained of how different weather variables are influenced by latitude. The linear regression analysis provides insights into weather patterns in the Northern and Southern Hemispheres.

Part 2: VacationPy

Introduction
In Part 2, the insights gained from Part 1 are used to plan future vacations. Jupyter notebooks, the geoViews Python library, and the Geoapify API are employed to create map visualizations and filter cities based on ideal weather conditions. The goal is to identify the perfect locations for future vacations.

Requirements
1. Interactive Maps: The project creates maps that display points for each city in the city_data_df DataFrame. The size of these points reflects each city's humidity.

2. City Filtering: The list of cities is narrowed down to find the ideal weather conditions. This may include criteria like a maximum temperature lower than 27 degrees but higher than 21, wind speed less than 4.5 m/s, and zero cloudiness.

3. Hotel Dataframe: A new DataFrame named hotel_df is created to store information about the nearest hotels. This DataFrame includes data on the city, country, coordinates, and humidity.

4. Find Nearest Hotels: For each city, the Geoapify API is used to find the first hotel located within 10,000 meters of the coordinates.

Usage
1. Jupyter Notebook: Open the provided VacationPy.ipynb Jupyter notebook. This notebook serves as the guide through the vacation planning process.

2. Execution: Run the notebook to generate the maps, filter cities, and identify the ideal vacation spots.

Results
By the end of Part 2, you will have a list of ideal vacation spots based on the specified weather conditions. These locations are displayed on interactive maps, complete with information about nearby hotels.