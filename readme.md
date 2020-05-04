# Summary of data visualisation
## by Seishu Miki


## Dataset

The data is Bay Wheels's trip data for public use which I downloaded from https://www.lyft.com/bikes/bay-wheels/system-data. In this project, I use the trip data in 2018.It conatains 1863721 unique data with various columns such as start time to hire bike and its trip duration. 

## Summary of Findings

I investigated the dataset from Ford GoBike. The purpose of investigation in this project is to find the patterns of bike rides by different people. The main focus this time is on the patterns of trip duration from different perspectives.

By analyzing start hour, start day and start month, it can be seen that there are popular periods in each unit. 8am and 17pm are the peak hours when more users start bike rides. In addition, weekdays are more popular than weekends in the unit of week. Compared with winter and early spring, summber is more popular season for bike hiring. 

Next, when looking into the trip duration im minutes, most users ride bikes for short time. 98 percent of trip durations is within 53 minutes, and also most of duration last between 0 to 20 minutes. In addition, Ttrip durtion minutes changes their patterns based on some variables. If you look at the difference of trip duration between users who shared bike on their trip and who didn't, you cannot see a clear difference. On the other hand, trip duration varies clearly with user type. The average of trip duration of customers is about 20 minutes longer than the one of subscribers. In this sense, we can predict that subscribers use bikes for shorter trips. Furthermore, trip duration changes on weekdays and weekends but in per month. Trip duration lasts longer by about 7 minutes on weekends than the one on weekdys. In contrast, there is no significant change between month.

Finally, I created plots of three variables to for further investigation. Subscribers' duration minutes are much shorter than customers' on each day a week. On the other hand, there is a common point for both user types. Trip duration of both user types increases on weekends.　Customers' trip duration varies slightly while subscribers show stable trip duration through weekdays. In conlusion, it can be seen that customers' and subscribers' trip duration has the similar pattern of changes through a week even though their average duration minuets are significantly different.


## Key Insights for Presentation

In this project, I limited scope of presentation to make it clearer. As mentioned, the main purpose of this analysis is to find the patterns of trip duration. Therefore, I use the data from the column: duration_min for all visualisations and only showed graphes with significant differences. I removed graphes which have similar patterns from the presentation.
 