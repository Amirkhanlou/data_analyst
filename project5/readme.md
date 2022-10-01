# Exploring the Ford GoBike System Data for San Francisco and Comparing with Mobi Bike Data for Vancouver

## Dataset

The bike sharing system data, after cleaning, consists of information regarding 2.8 million rides in the city of San Francisco and 0.7 millions entries for the city of Vancouver spanning over full year of 2019 and the first 4 months of 2020. The extracted features for analysis are duration, start time, end time, user type, time of day, day of week, month of year and year.

The original data for San Francisco is downloaded from: https://www.lyft.com/bikes/bay-wheels/system-data
The data for Vancouver is downloaded from: https://www.mobibikes.ca/en/system-data


## Summary of Findings

In this exploration, I found that the bike ride duration (presented in seconds) have a highly right skewed distribution for both data set. When I did the axis transformation, they both turned into perfect shape bell curve which is useful for modelling should someone pursue that.
In general Vancouver rides have longer duration which remained consistent between 2019 and 2020. On the other hand, there are a lot more users in San Francisco who tend to use bike sharing service, however they tend to go for relatively shorter distance when compared to Vancouver. San Francisco users also showed an increase in ride duration for the first 4 months of 2020 when compared to 2019.
The users of both cities tend to go for longer duration bike ride during the weekends and there is not too much seasonal effect on the ride duration for San Francisco user where Vancouver users tend to stick to drier months.
In San Francisco, the user also takes the longest rides in average during the afternoon and the users are without subscription tend to go for longer rides comparing to the subscribers. 
The membership types in Vancouver is much more complex than San Francisco and consists of 21 different membership type, with "24 Hours" and "30 Day Pass" being the most popular membership type and "Single Trip Pass" users going for the longest duration of rides.

Despite the non-subscriber membership types going for longer rides in San Francisco they account for much smaller number of trips and
Jan, Feb, and Mar account for the highest number of the trips with Feb being the most popular time to ride
First 4 months of 2020 shows an increase in using the bikes in general in San Francisco however there is not a major change in 2020 usage in Vancouver.
San Francisco data also shows a major drop in the number of bike rides in the weekends for 2019; however, this drop is less pronounced in 2020. The lower height of the bars for 2020 is due to less data collection since we only have the data for the first 4 months of 2020.

The data also shows that regardless of what year, month, or day of week, majority of the trips were under 2000 seconds in San Francisco while the trips in Vancouver tend to stretch into 4000 seconds mark. Another finding is that the non-subscriber/member user types seem to have a larger variance in the trip duration for both cities while the subscribers tend to go for more consistent ride duration which might mean they probably use it for some fixed trip length such as commute to work and back

Another interesting finding is that, in 2020, duration of the rides increased by about 7% in San Francisco however there is no such an obvious change for Vancouver.


## Key Insights for Presentation

For the presentation, the main feature is the ride duration and the impact of city, type of user, day of week, time of day, month of year and year on it is investigated. One of the key interesting things I was looking for was any obvious change in using bike sharing system during the first 4 months of 2020 when COVID-19 pandemic hit the entire world. Interestingly the data shows the bike duration had slight increase in duration in 2020 especially in San Francisco however the data also implied the user may have held on to the bikes longer fearing the spread of virus from touching public surfaces. This is inferred in the presentation by looking at the two plots where the count of trips is shown per month and type of users.

I have also introduced multiple plots afterward showing the behaviour of the users as per time of day and day of week and month of year and year