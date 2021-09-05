__August 16, 2021__


### Data Exploration ‒ Ford GoBike Tripdata
This project was written for Udacity’s Data Analyst nanodegree program. The primary goal is to demonstrate the importance and value of data visualization techniques in the data analysis process. For this purpose, the Ford GoBike dataset was chosen and wrangled. This dataset contains basic information about individual rides made in this bike share system.

### Software required
* Python 3

### Files used
* 201902-fordgobike-tripdata.csv
* communicate-data-findings_gabriela-trindade.ipynb

### Dataset
Ford GoBike is a regional public bicycle sharing system in San Francisco Bay Area. The system was originally launched as Bay Area Bike Share in August 2013, but it was re-launched in 2017 after the sponsorship of Ford. Like other bike share systems, it consists of a fleet of bikes that is locked into a network of docking stations throughout the city. The bikes can be unlocked in one station and returned to any other station in the system, making them ideal for one-way trips. After becoming a member or purchasing a pass, riders will have access to all bikes in the network.
After the dataset was cleaned, there are 174,952 rows and 24 columns. In summary, this dataset contains variables about:
* trip: start/end date (month, day and hour) and its duration in seconds and minutes;
* stations: start/end stations, their names and geolocations (latitude/longitude);
* anonymized customer data: gender, birth date, age and user type.

### Main Findings
In this analysis, I was most interested in figuring out how genders ("member_gender") differ from each other in the use of this bike service, concerning the users age, the trip duration, and the day and hour that this trip starts.

The data exploration demonstrated that there were no important differences observed in the way the differnt genders use the bicycle sharing system, in terms of the selected variables. All genders show similar distributions of bike ride duration, although male users usually take slightly shorter rides. The three genders frequency per age group also follows a similar trend, with greater values in the 30-40-year-old group. Therefore, this bike service appears to be more frequently used by a more mature public. Finally, regardless of their gender, users usually take rides during the weekdays, with peak hours of rentals corresponding to rush hours periods, when employees are expected to travel to and from work.

### References
* https://www.geeksforgeeks.org/convert-birth-date-to-age-in-pandas/
* https://stackoverflow.com/questions/43956335/convert-float64-column-to-int64-in-pandas
* https://stackoverflow.com/questions/51603690/extract-day-and-month-from-a-datetime-object
* https://stackoverflow.com/questions/18674064/how-do-i-insert-a-column-at-a-specific-column-index-in-pandas
* https://stackoverflow.com/questions/17582137/ipython-notebook-svg-figures-by-default
* https://stackoverflow.com/questions/36519086/how-to-get-rid-of-unnamed-0-column-in-a-pandas-dataframe
* https://medium.com/@morganjonesartist/color-guide-to-seaborn-palettes-da849406d44f
* https://www.dataforeverybody.com/seaborn-legend-change-location-size/
