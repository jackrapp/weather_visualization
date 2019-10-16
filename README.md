# Temperature vs Latitude

See how weather varies by latitude

Deployed at: 

## Project Summary

### Data Collection

To gather weather data, pairs of coordinates were selected at random using a random number generator, latitude range from -90 to 90, longitude range -180 to 180. 1500 datapoints were input into the library citypy with the goal of ending up with 500 cities to compare.

#### Add histogram to show distribution of lats/cities

Using the generated list of cities and OpenWeatherMap's API, weather data was uploaded into an empty data frame. Any cities with no weather stations are ignored and every 60 cities the API pauses to avoid the API request limit.

#### Add sample API code

### Data Visulaization and Analysis

Using matplotlib and the library pyplot, temperature, humidity, cloudiness and windspeed are all graphed against latitude. These charts can be seen at:

#### Visualizations and conclusions

