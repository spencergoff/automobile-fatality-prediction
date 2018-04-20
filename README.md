# automobile-fatality-prediction

### About the Project
Attempts to accurately predict the number of fatalities caused by automobile-related incidents given the hour, day of the week, and the current weather conditions. 

### About the Data
The files auto_fatalities.csv and auto_fatalities_numeric.csv were organized by me using data from https://www-fars.nhtsa.dot.gov/QueryTool/querysection/selectyear.aspx

I documented the steps I took to query this data in automobile-fatalities-query-steps.pdf.  

auto_fatalities.csv contains data in which the day, hour, and weather fields are kept human-readable

auto_fatalities_numeric.csv contains data in which the day, hour, and weather fields are assigned discrete values as listed below. In order for the data to work with the regression model, I had to assign numerical descriptors to each of the possible non-numeric values. Here are the corresponding values:

Sunday: 0
Monday: 1
Tuesday: 2
Wednesday: 3
Thursday: 4
Friday: 5
Saturday: 6

0:00am-0:59am: 0      12:00pm-12:59pm: 12
1:00am-1:59am: 1      1:00pm-1:59pm: 13
2:00am-2:59am: 2      2:00pm-2:59pm: 14
3:00am-3:59am: 3      3:00pm-3:59pm: 15
4:00am-4:59am: 4      4:00pm-4:59pm: 16
5:00am-5:59am: 5      5:00pm-5:59pm: 17
6:00am-6:59am: 6      6:00pm-6:59pm: 18
7:00am-7:59am: 7      7:00pm-7:59pm: 19
8:00am-8:59am: 8      8:00pm-8:59pm
9:00am-9:59am: 9      9:00pm-9:59pm: 21
10:00am-10:59am: 10   10:00pm-10:59pm: 22
11:00am-11:59am: 11   11:00pm-11:59pm: 23

Clear: 0
Rain: 1
Sleet or Hail: 2
Snow: 3
Fog or Smoke or Smog: 4
Severe Crosswinds: 5
Other: 6
Cloudy: 7
Blowing Snow: 8
Freezing Rain or Drizzle: 9











### About the Regression Model


### Disclaimer
Note that this is simply an amateur project, and its results are not meant to be used in place of professional knowledge or recommendations. 

