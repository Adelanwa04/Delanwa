docs: Ford GoBike Data Visualization
      by Taiwo Adelanwa


Dataset

The Ford GoBike system dataset provides anonymized, timestamped data about the start- and end- station for a bike, the user type (subscriber or casual rider), as well as some customer-reported attributes like birth year and gender. This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. This project analyzes the data collected from users of the GoBike program.

This dataset includes 183412 rows and 16 columns data entries:

- An ID number for each bicycle
- How long it was rented for, in seconds
- The beginning and end staton ID, latitude, longitude and station name
- Start time and end time
-  The birth year of users
- Gender of the users
- Subsription type of users, among others
- I did some wrangling which included:

- Categorising start_station_id, end_station_id, user_type, member_gender, bike_share_for_all_trip
- Converting bike_id to string
- Adding a column for distance in kilometers, based on the longitude and latitude start and end points (feature engineering)
- Calculating the users' age from users' birth year
- Adding age group column from users' age
- Extracting days of the week and time of the day from start time
- Converting time of the day from 24hr to 12hr time

Summary of Findings

- I was able discover different trends and uncover insights when i analysed FordGo Bike dataset. Most of the trips travelled for 500-800 seconds per ride with a frequency of more than 12,000. Most riders are male accounting for over 120,000 rides which is more than double the female and other gender combined. I also discovered that 89.2% of rides were from subscribers, while just 10.8% were customers paying daily.

- Suprisingly, I discovered more than 20,000 bike trips were taken at 8am and 5pm on Tuesdays and Thursdays. The time of the day is when the weather is expected to be cooler and conducive for relaxation and riding.The majority of users are middle-aged adult with over 120,000 rides with both adolescents and old-aged adults following in distance with about 20,000 riders respectively. This is to be expected as the middle-aged adult tend to be more adventurous.

- From my analysis, I was able to note that long distant rides were rarely taken. Most of the rides are of short distances with short durations. Which lies in the range of under 30000 secs and 9 Kms. Also, most of the trips were taken by Middle-aged Adult(25 - 44yrs) which was on Thurdays and Tuesdays. Seniors(65+ yrs) took the least trips in all days of the week.

Key Insights for Presentation

For my presentation, I will focus on the difference in usage for customers and subscribers. On the later plots, I will show how gender and age groups come into play. I will first show the univariate results, such as usage on days of the week, time of the day. I will then continue to see how adding more variables influences the results. My conclusion is that whether age group has the biggest influence on results, compared to gender.


