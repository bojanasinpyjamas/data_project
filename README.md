# data_project

CoDe1161 data project
SO confusing
This is cool
https://experience.arcgis.com/experience/7fe4798902f64068819586a1035e26ba

How many rows and columns?
count
Unstack the data function not ideal
Date column
Location
Mode
Direction?
Count?

str(name) page
parse dates?

How many rows and columns?

- 43329 rows and 6 columns
  What does the dataset explain?
- How many cyclist and pedestrians are travelling in a certain direction on a certain day over 3 years
  Why was it collected?
- Who paid for it?
- Transport NSW
  Where did you get it from?
- https://opendata.transport.nsw.gov.au/
  Does it have a geographical component?
- Yes, location of counter
  Description of columns:
- Date: shows the date, records the date the data was collected
- Location name: shows the name of the location of the counter
- Location code:
  Is it continuous or categorical data?
- Continous
  If continuous:
- do a df["column_name"].hist() to get an idea of what your numbers are and how they’re distributed.
- Is it a time series? A time series is data that changes over time, like the temperature at my desk, or the number of cookies I have left in the packet. If it is a time series
  - do a df["column_name"].plot() to see the trends.
  - are there any periods of time that are missing data? E.g. did they turn it off over the weekends?
- What’s the biggest value (max)?
- What’s the smallest value (min)?
- What’s the mean value (mean)?
- What’s the median value (median)?
- What’s the most common value (mode)?
- make some general comments about this column, based on what we see.
- make some general comments about the dataframe, based on what we see.
