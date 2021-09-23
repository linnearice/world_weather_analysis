# World Weather Aanalysis

## Purpose
DAI, Inc. ("DAI") was hired by a travel company to perform real-time suggestions for their client's most ideal hotels. Specifically, hotels that are within a given range of latitude and longitude and hotels that are in cities with the right kind of weather for the client.

To that end, DAI conducted the following research:

### First Data Meeting
  * Created a set of 2,000 random latitudes and longitudes.  
  * Searched for the nearest city using citipy module.
  * Performed an API call with OpenWeatherMap.
  * Retrieved the following information from the API call:
      * Latitude and longitude
      * Maximum temperature
      * Percent humidity
      * Percent cloudiness
      * Wind speed
      * Weather description
  * Created a new DataFrame of the data and saved to a CSV file

### Second Data Meeting
  * Developed process where clients can input their weather temperature min and max temperature options to obtain a list of potential vacation destinations.
  * For this list DAI also provided hotel names for each destination.
  * DAI also mapped the potential destinations with provided popup markers to give the clients the hotel name, city, country, maximum temperature and weather description.

### Third Data Meeting
  * Based on the clients selection of 4 choice destinations for one trip, DAI used Google Directions API to provide the client details about their upcoming trip.
  * DAI provided a map showing a driving route for travel to each of their 4 destinations.
  * DAI also provided a map with pop markers giving the client information for each of the 4 cities: Hotel Name, City, Country, Weather Description and Maximum Temperature.
  
The meetings were successful and provided their clients with meaningful information to begin their travels.
