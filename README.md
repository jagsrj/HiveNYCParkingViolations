# HiveNYCParkingViolations
NYC Parking violation data analysis using HIVE - BIG DATA

Part-I: Examine the data
1. Find the total number of tickets for the year.
2. Find out the total number of states to which the cars with tickets belong. The count of states is mandatory here; providing the exact list of states is optional.
3. Some parking tickets don’t have addresses on them, which is a cause for concern. Find out the number of such tickets which have no addresses. (i.e. tickets where one of the Street Codes, i.e. "Street Code 1" or "Street Code 2" or "Street Code 3" is empty)


Part-II: Aggregation tasks
1. Find out the frequency of parking violations across different times of the day: The Violation Time field is specified in a strange format. Find a way to make this into a time attribute that you can use to divide into groups.

2. Divide 24 hours into six equal discrete bins of time. The intervals you choose are at your discretion. For each of these groups, find the 3 most commonly occurring violations.
3. Now, try another direction. For the 3 most commonly occurring violation codes, find the most common times of day (in terms of the bins from the previous part).
4. Let’s try and find some seasonality in this data:
a) First, divide the year into seasons, and find the frequencies of tickets for each season. (Hint: A quick Google search reveals the following seasons in NYC: Spring(March, April, May); Summer(June, July, August); Fall(September, October, November); Winter(December, January, February))
b) Then, find the 3 most common violations for each of these seasons.



