# Ford GoBike System Data Analysis
## by Luke Confait

## Dataset

The data set contains information of 183,412 bike trips taken by users of the Ford GoBike bike sharing service during February 2019. The data includes information about the trip duration, the date and time when the trip takes place and the type of user in categories such as whether they are a subscriber or a customer. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

Some initial wrangling was performed to remove null values. A distance from start to end station feature was engineered from the data and the start and end time converted to start and end date and hour as well as day of week for the start of trips.

## Summary of Findings

The exploration found the Trip duration and distance from start to end station to be unimodal with a roughly normal distribution after transforming the data to a logarithmic scale. 

More trips were found to occur during the week compared with the weekend. The most frequent trips occured at the peak times for commuting to and from work indicating one of the primary use case of the service.

It was found that there was a linear trend in the minimum time to travel a certain distance from start to end station the correlation was fairly weak however.

Looking at categoric variables it was found that female and other gender users took longer trips than males and customers took longer trips than subscribers.

Trips took longer on the weekends but tended to be between closer stations. This is likely due to leisure trips happening on weekends and work trips on weekdays.

The main topics of interest for the presentation are the weekly and hourly use trends, as well differences over the week for trip duration and distance from start to end station.


## Key Insights for Presentation
 
The first key insight for the presentation is the distribution of trips during the days and weeks. The plot of trip count per day of week and per hour of day will be used at first followed by the heatmap of both variables to give further insight.

The second insight will be based on the average trip duration and distance between start and end station comparing the customer and subscriber user types. The trip count of each user type will show who uses the service more. A violin plot of the trip duration and distance will then show how the trips vary for these user groups.
Finally weekly trends in the average duration and distance will be used to show how this varies during the week for the two user types.



