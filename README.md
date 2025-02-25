# bike-share-forecast
Forecast the demand for the BA Ecobice bike share system.

- Data source: BA Data
- Exploratory data analysis
    - rows with empty t_start and t_end values
    - rows with empty lon and lat values for start and end station
    - validate trip_length from t_start and t_end
    - reconstruct any trip when t_start or t_end is missing when trip_length is available.
- Feature engineering:
    - datetime
        - workday
        - holiday
        - seasson
    - weather
        - temperature
        - wind
        - rain
        - humidity
    - geography
        - proximity to parks
        - distance to downtown