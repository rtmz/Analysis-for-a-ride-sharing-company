# Analysis-for-a-ride-sharing-company
The task is to find patterns in the available information on rides. We want to understand passenger preferences and the impact of external factors on rides. We'll  analyze data from competitors, and test a hypothesis about the impact of weather on ride frequency. 

# We'll go through the following steps:

**Exploratory data analysis**

We have these two CSVs:

  _project_sql_result_01.csv_. 
  
It contains the following data:
  - _company_name_: taxi company name
  - _trips_amount_: the number of rides for each taxi company on November 15-16, 2017.
_project_sql_result_04.csv_. It contains the following data:
  - _dropoff_location_name_: Chicago neighborhoods where rides ended
  - _average_trips_: the average number of rides that ended in each neighborhood in November 2017.

For these two datasets we need to:
- import the files
- study the data they contain
- make sure the data types are correct
- identify the top 10 neighborhoods in terms of drop-offs
- make graphs: taxi companies and number of rides, top 10 neighborhoods by number of dropoffs
- draw conclusions based on each graph and explain the results

**Testing hypotheses** 
_project_sql_result_07.csv_ — the result of the last query. 

It contains data on rides from the Loop to O'Hare International Airport. Remember, these are the table's field values:

- _start_ts_ -  pickup date and time
- _weather_conditions_ - weather conditions at the moment the ride started
- _duration_seconds_ - ride duration in seconds

Test the hypothesis:

  `"The average duration of rides from Loop neighborhood to O'Hare International Airport changes on rainy Saturdays." `
