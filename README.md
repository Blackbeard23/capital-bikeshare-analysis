# Analysis of Capital Bikeshare of Washington, D.C in 2021
## by Ajibade Adeleke


## Dataset

The data consists of approximately 2.7M bike rides with 13 features, with features of interest such as start/end station name, bike ride type, and user type. Trips with less than 60 seconds and on the same station were removed as they could be potentially false starts or users trying to re-dock a bike to ensure it's secure. The data can be found [here](https://s3.amazonaws.com/capitalbikeshare-data/index.html), with features documentation [here](https://ride.capitalbikeshare.com/system-data).


## Summary of Findings

Univariate exploration: There are two types of clients using the system; Member, having 60%, and Causal having 40% of total trips with the classic bike being the most preferred bike type. There was an increasing number of trips in early Spring (March) up till October(Fall) where it was the highest number of trips by Month. 4th of July which is a federal holiday in the United States commemorating the Declaration of Independence was the highest recorded trip per day. More trips were made on the weekend(Sat & Sun) than on the weekdays, and an increasing number of trips from 8 am up until 5 pm which is the peak of the trip made during the hours of the day.  

Bivariate Exploration: There were longer trip durations for casual users than Members, longer durations during the weekend than weekdays, and longer durations in March & April. Among the most popular start/end stations, there were more casual users than members around those parts. Classic bike is most preferred by both users as a type of bike.

Multivariate Exploration: separating user types, Casual and Member, gives more insights and the behavior of users. Members are most active during weekdays during commute hours 7 am to 8 am and 5 pm to 7 pm, and occasionally around lunchtime with way less activity on the weekends. Unlike Member users, Casual clients are more active during the weekend from 9 am to 7 pm. And sometimes active during the late evening (5 pm - 7 pm) of all days of the week which could mean an evening stroll.


## Key Insights for Presentation

For the presentation, I focus on customer habits in 2021. Since capital bikeshare System currently offers 2 subscription types: Member and Casual. I start by introducing number counts and the percentage of customers who use the system occasionally and those who have a membership. Afterward, I move to the bike type mostly used by customers and then trend analysis of bike counts by month and day. I use the heatmap to show when bikes are high in demand throughout the week and hours of the day.