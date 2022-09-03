# Project Name: Covid19-Report

# Problem Statement
* Top Five Countries with the Highest Confirmed Covid'19 Cases in the World.
* Bottom Five Countries with the Lowest Confirmed Covid'19 Cases in the World.
* What is the cumulative Monthly report of Covid'19 cases?.
* What is the cumulative Yearly report of Covid'19 cases?.

# Data sourcing Phase:
The data used for this analysis was obtained on Github https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series in CSV file format.
It was stored in a spreadsheet in xlsx file format.

# Data Transformation Phase:
Using Excel Power Query, the following operation was performed;
* Other Columns were unpivoted except the Province, country, latitude and longitude columns to make the data easy to work with.
* The unpivoted columns were summarised into two columns namely date and Confirmed cases respectively and the process was repeated for death cases and recovered cases data.
* The three data were merged using inner join ( Country, Province and Date).
* Also, the new consolidated data was formatted into a table with each column given its appropriate data type ( Text, Whole Number, Date).
* Lastly, three additional columns were inserted each for Year Values, Month values and date values which were obtained from the date column.

# Insight:
* The USA country has the highest confirmed cases with the death rate of 9.44%.
* Korea North Country has the lowest Confirmed reported cases of covid'19.
* From the  Monthly cumulative reported cases, the Month of May has the Confirmed Covid'19 cases.
* From the  Yearly cumulative reported cases, 2022 has the highest Confirmed Covid'19 cases.

Note; this analysis was limited to confirmed cases due to an incomplete dataset on the reported Recovered covid'19 cases.
