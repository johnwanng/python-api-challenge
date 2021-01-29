# python-api-challenge

## Introduction

There are two parts in this project. The first part consists of two requirements and they are described below.

The first requirement is to create a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude


Each of four plots were stored as png files inside the 'Images' folder.  

The following are three observable trends based on the weather data:

The correlation coefficient calculated between temperatures and latitudes of cities is  -0.7652381363577664 and this value is between -0.5 to -1 which indicates a strong relationship between temperatures and the latitudes of the cities. The scatter plot represented in the 'Scatter-Temperature (F) vs Latitude of sample 600 cities.pgn' has indicated higher temperature cities tend to located on lower latitudes coordinates of cities used in the sample data.

The correlation coefficient calculated between Humidity (%) and latitudes of cities. Is 0.2911472933999017 and this value is below 0.5 which indicates a weak or no relationship between humidity percentage and the latitudes of the cities. The scatter plot represented in the 'Humidity (%) vs Latitude of sample 600 cities.png' has NOT provided any evidence or relationship between humidity percentage and latitudes of those cities used in the sample data.

The correlation coefficient calculated between Cloudiness (%) and latitudes of cities. Is 0.1313450021224035 and this value is below 0.5 which indicates a weak or no relationship between humidity percentage and the latitudes of the cities. The scatter plot represented in the 'Cloudiness (%) vs Latitude of sample 600 cities.png' has NOT provided any evidence or relationship between humidity percentage and latitudes of those cities used in the sample data.

The correlation coefficient calculated between Wind Speed (mph) and latitudes of cities. Is -0.0017078635489743289 and this value is very close to 0 which indicates a weak or no relationship between humidity percentage and the latitudes of the cities. The scatter plot represented in the 'Wind speed (mph) vs Latitude of sample 600 cities.png' has NOT provided any evidence or relationship between wind speed and latitudes of those cities used in the sample data.



The second requirement is to run linear regression on each relationship, only this time separating them into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude


The second part will require the use jupyter-gmaps and the Google Places API to draw a world map of the heatmap from the data collected in the first part of the project. The heztmap image is stored as 'Humidity Heat Map with Hotels.png' inside the Images folder.



# Technologies
 
Python 3.8.5
 
## Setup 

1. Download and extract the zip file

2. Open Terminal (on Mac) or Open Bash (on PC)

3. Navigate to the python-api-challenge folder

4. Open the WeatherPy.ipynb file to run the first part of the project.

5. Run each segment of the file to retrieve those summary information described above.

6. Open the VacationPy.ipynb file to run the second part of the project.

7. Run each segment of the file to display the heatmap.