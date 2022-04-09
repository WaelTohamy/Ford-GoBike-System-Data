Data wrangling process:

1. Missing Data as Columns (member_birth_year, member_gender, start_station_id, start_station_name, end_station_id, end_station_name)
2. The Data Type need to modify as Columns (start_time, end_time )
3. Add some additional modifications to data set
	Add new column for trip duration in minute 'duration_minute'
	Add new column for trip duration in minute 'duration_hour'
	Add new colum for start date in yyyy-mm-dd format 'start_date'
	Add new colum for trip start hour of the day 'start_hourofday'
	Add new colum for day of week and month 'start_dayofweek'
	Add new colum for day of month 'start_month'
	Add a new column calculating riders' age 'member_age'
4. Delete some Columns which is not used in my analysis
	start_station_latitude
	start_station_longitude
	end_station_latitude
	end_station_longitude

The Summary:

1. It is quite Observed that the majority of rides happened in hours around two timeframes, 7am-9am and 16pm-18pm
2. It is quite Observed that the majority of rides happened on work days (Tuesday-Tursday) and miniorty od rides happened on Weekend days (Saturday and Sunday)
3. It is Observed that the majority riders is Subscribers
4. It is Observed that the majority riders is Male
5. It is Observed that the majority riders age is between 25 year to 35 year
6. It is Observed that the majority Duration between 5 to 10 minutes
7. Subscriber user is the shortest Duration
8. Male members is the shortest Duration
9. Saturday and Sunday is the longest Duration
10. the riders who used the bicks in saturday and sunday is more youngest
11. Customer riders is the youngest
12. The subscribers ride much shorter trips compared to customers
13. Male riders are the shortest trips