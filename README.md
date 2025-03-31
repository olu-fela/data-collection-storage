# Data Collection and Storage Project (TripleTen Bootcamp)

This repository contains a Jupyter Notebook with interactive maps.

[View the interactive notebook here](https://nbviewer.org/github/olu-fela/data-collection-storage/blob/main/project.ipynb)

<hr>

Working as an analyst for Zuber, a new ride-sharing company that's launching in Chicago, and tasked to find patterns in the available information. 
Goal is to understand passenger preferences and the impact of external factors on rides.

Working with a database, will analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.

**Description of the data**

Worked with datasets with info on taxi rides and weather details in Chicago:

1. **Car Company dataset** - `/datasets/moved_project_sql_result_01.csv`. It contains the following data:
    - `company_name`: taxi company name
    - `trips_amount`: the number of rides for each taxi company on November 15-16, 2017.

2. **City neighborhoods dataset** - `/datasets/moved_project_sql_result_04.csv`. It contains the following data:
    - `dropoff_location_name`: Chicago neighborhoods where rides ended
    - `average_trips`: the average number of rides that ended in each neighborhood in November 2017.

3. **Data Rides dataset** - `/datasets/moved_project_sql_result_07.csv`. It contains data on rides from the Loop to O'Hare International Airport.
    - `start_ts`: pickup date and time
    - `weather_conditions`: weather conditions at the moment the ride started
    - `duration_seconds`: ride duration in seconds
