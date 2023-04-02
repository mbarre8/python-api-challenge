# python-api-challenge
In the following challenge there are two parts:

Part 1 (WeatherPy):
    In WeatherPy I used citipy, matplotlib, pandas, numpy and wrote a python script to visualize weather over 500+ random cities in the world. We analyzed latitude, temperature, humidity, cloudiness, and wind speed for each city and then looked at cities in the northern hemisphere vs southern hemisphere.
    
    In the Northern Hemisphere there is a negative correlation between Latitude and Maximum temperature as Latitude increases the Temperature decreases. The Southern Hemisphere has a positive correlation between Latitude and Maximum temperature as Latitude increases the Temperature increases.
    
    Both the Northern and Southern Hemisphere have a positive correlation between Latitude and Humidity. But for both hemispheres the relationship between Latitude and Humdity does not display a strong correlation between the two variables. But overall trend if Latitude increases Humidity increases.
    
    Both the Northern and Southern Hemisphere have a positive correlation between Latitude and Cloudiness. But for both hemispheres the relationship between Latitude and Cloudiness does not display a strong correlation between the two variables. But overall trend if Latitude increases Cloudiness increases.
    
    In the Northern Hemisphere there is a slightly positive correlation between Latitude and Wind Speed as Latitude increases the Wind Speed increases. But the corrleations between the two variables is not strong and looks like wind speed stay within the same range for the most part. The Southern Hemisphere has a slightly negative correlation between Latitude and Wind Speed as Latitude increases the Wind Speed decreases.But the corrleations between the two variables is not strong and looks like wind speed stay within the same range for the most part.
    
Part 2 (VacationPy):
    In VacationPy I used geoviews, hvplot, pandas, requests and wrote a python script to plot cities found in weatherpy in a map with humditiy data. In addition, we narrowed down the dataset for ideal weather conditions and found the first hotel with 10000 mile radius of the cities coordinates and placed all information on map.
    
