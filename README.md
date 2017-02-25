# Houston Hobby Airport data

For this month's [data jam](https://www.meetup.com/Houston-Data-Visualization-Meetup/events/237127703/), we will be working with data from Monday at the Houston Hobby airport.  This data is sourced from FlightAware's API.

We have the data available in **csv**, each in their respective directories.

## Data

The data are found in the following files:

1. **weather.csv**: weather.csv -- Weather at the airport for the time-period

  |Column|Description|
|----|----------|
|airport| Airport code; will be 'KIAH' for this dataset|
|time| Epoch time ([see here for more info](https://en.wikipedia.org/wiki/Unix_time))|
|cloud_friendly| Cloudy/Clear/Etc.|
|cloud_altitude| Height of clouds (99999 if Clear)|
|cloud_type| Abbreviated Cloud description|
|conditions| None|
|pressure| barometric pressure (inHg)|
|temp_air| air temperature (Celsius)|
|temp_dewpoint| dewpoint (Celsius)|
|temp_relhum| relative humidity|
|visibility| visibility range (statute miles)|
|wind_friendly| e.g. 'Windy'|
|wind_direction| wind direction (knots); 360 means true north|
|wind_speed| wind speeds (knots)|
|wind_speed_gust| gust speeds (knots)|
|raw_data| METAR data used by pilots, e.g.'KIAH 250453Z 36015G22KT 10SM CLR 16/04 A2995 RMK AO2 SLP142 T01610044'
