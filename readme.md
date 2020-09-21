# (Ford GoBike System Data)

## by (Zhang Zhen Jenny)

**Introduction**
>Ford GoBike or Bay Wheels is a regional public bicycle sharing system in California's San Francisco Bay Area established in 2013. Till January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. And Ford GoBike is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States.

>In this project, data visulization will be performed by using univariate, bivariate, and multivariate plots to explore the Ford GoBike users behaviour during current pandemic situation from Apr to Aug 2020, some of the patterns such as trip usage throughout hour of day, day of week etc will be compared with dataset from Apr to Aug 2019. Those observation could be beneficial for Ford GoBike's operation optimization and allocate sufficient resources during the time of day and day of each week.

## Dataset
> As the project focuses on the Ford GoBike user behavior, extracted dataset in Apr to Aug 2020 from https://www.lyft.com/bikes/bay-wheels/system-data. Meanwhile, to better understand the change in trend, dataset in Apr to Aug 2019 also collected for the analysis. 

> Once dataset collection completed, basic data cleaning was performed to drop columns irrelevant to this analysis. Used function to calculate distance of each trip based on start and end latitude and longitude. Columns of year, month, week, hour and duration were created from extracted time date from start_at column.


> After data cleaning, the features to be investiged will be focused on:

- Ride ID
- Trip Duration
- Start Time and Date
- End Time and Date
- Distance of each Trip
- User Type (Member or Casual)
- Rideable type (Electric Bike or Docked Bike)

## Summary of Findings

**Through the data exploration of Ford GoBike's system data collected from Apr to Aug 2020, some meaningful insights are uncovered:**

>1. Overally, trip duration of users is within 30 minutes, due to the pricing method of Ford GoBike.

>2. From Apr to Aug 2020, there are 40.5% (around 280000) of users are members under subscription and 59.5% (around 400000) are casual customers. But in the same period of 2019, there are 82.9% (more than 800000) subscribers and 17.1% (less than 200000) casual customers.

>3. The highest number of trips appeared at June 2020 and especially during weekends (Saturday and Sunday), it attracted more users. Throughout the day, the number of trips increased steadily from 7am to 5pm and reached to the peak at 5pm, but it dropped rapidily after 5pm.

>4. In 2020, users tended to be more active during weekends and the trend applied largely to casual users. However, for subscribers or members, the number of trips spread quite evenly in each day of week. On contrast, subscribers in 2019 generate most of the trips and they are more active during Monday to Friday. But during weekends, the number of trips dropped by 50%. In addtion, trips made by casual users were evenly spreaded out in each day of week.

>5. Casual users have longer trip duration compares with subscribers, ranging from 500 to 1500 seconds; subscribed users generally have trip duration of 400 to 1200 seconds.

>6. For the trend in trips made in different hour of the day, peak bike sharing usage in the morning (8am) and evening (5pm) hour in 2019. Trips are mostly produced by subscribers, but this trend also fits casual users.

>7. The pattern of users' travelling distance in susbcriber and casual users are quite similar, from 1km to 3km.

>8. No positive correlation between duration and distance in both subscriber and casual users was noticed. It can be observed that most of the users' trip distance is within 12.5 km and trip duration is within 4 hours.

>9. The trip demand is highly densed from 7am to 8pm over each weekday, however, for casual users, they are more active on weekends, from 10am to 7pm.

>10. Generally, there are higher usage for electric bike over docked bike, but from 10am to 7pm, both electric bike and docked bike showed more densed user trip, which means higher demand in the period of time.


## Key Insights for Presentation

> The change in user behavior is drastic during this pandemic period. From Apr to Aug 2020, it is observed that users were more active during weekends instead of weekday (monday to Friday), which is quite opposite to the trend in 2019. There are no morning(8am) or evening(5pm) peak hour trips in 2020, throughout the day, the number of trips increased steadily from 7am to 5pm and reached to the peak at 5pm, and it dropped rapidily after 5pm. This finding actually match the current situation in different workstyle, we are mostly experiencing work from home for now. Moreover, with reduced travelling demand, from Apr to Aug 2020, there are 40.5% (around 280000) of users are members under subscription and 59.5% (around 400000) are casual customers. But in the same period of 2019, there are 82.9% (more than 800000) subscribers and 17.1% (less than 200000) casual customers. More casual users are noticed which might due to the uncertainty raised by pandemic situation. As a result, it is recommended to allocated more resource during weekends to better meet travelling demand from existing users and discount or promotions could be implemented when the covid situation stablized to boost the subscription rate.


```python

```
