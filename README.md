
### Weather Py

1. Series of scatter plots
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude
1.1 Add brief analysis
2. Series of Linear regression
This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

- Northern Hemisphere: Temperature (F) vs. Latitude
- Southern Hemisphere: Temperature (F) vs. Latitude
- Northern Hemisphere: Humidity (%) vs. Latitude
- Southern Hemisphere: Humidity (%) vs. Latitude
- Northern Hemisphere: Cloudiness (%) vs. Latitude
- Southern Hemisphere: Cloudiness (%) vs. Latitude
- Northern Hemisphere: Wind Speed (mph) vs. Latitude
- Southern Hemisphere: Wind Speed (mph) vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

Your final notebook must meet the following requirements:

- Randomly select **at least** 500 unique (not repeated) cities based on latitude and longitude.
- Perform a weather check on each of the cities by using a series of successive API calls.
- Include a print log of each city as it's being processed, with the city number and city name.
- Save a CSV of all retrieved data and a PNG image for each scatter plot.