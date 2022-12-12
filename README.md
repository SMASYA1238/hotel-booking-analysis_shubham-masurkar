# hotel-booking-analysis_shubham-masurkar
The hotel industry is subdivision of the hospitality industry that specializes in providing customers with lodging services. There are a variety of hotel types that typically can be categorized by size, function, service, and cost. Levels of service can usually be split into three options: limited-service, mid-range service, and full-service. A hotel booking Dataset of 119390 entries was given to perform Exploratory Data Analysis (EDA)to analyse and find solutions from hotel business prespective.

The first step was to import and understand the data. Before importing the data, all the necessary libraries such as Numpy, Pandas, Matplotlib & Seaborn were imported. The data was imported under the variable name df and first 5 rows were viewed to comprehend the data. To understand each variable, the data type was checked for each variable.

Further inspection of the dataset showed some null values as well as duplicated values. The duplicate values were dropped from the dataset.Also the null values in the Dataset were taken care by replacing it with values best suited. The columns also had "zero" values, which was replaced by mean values of that particular subgroup and the dataset was ready for EDA.

After the EDA, following conclusions were drawn:

City hotels have double the amount of reservation compared to resort hotels for same time period.
City hotels have high cancellation rates compared to Resort hotels.
Reservations for both type of hotels peak in August and is lowest in the month of January.
Majority of the reservation is by 2 adults followed by few family with 1 or 2 children.
Bookings for city hotels are higher than resort hotels by considering every years data except the year 2015.
In the year 2016 both the hotels have the highest number of guests.
Both the hotels have good occupancy in the 2nd and 3rd quarter of the year with 'August' being the highest of all.
Here we can conclude that the bookings in the month end are least. But that not true because as every month didn't have the 31 days thats why we see the less number of arrivals in the month end.
Most people prefer to stay at the hotels for upto 5 days.
