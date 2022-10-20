# Ford GoBike System Data Analysis
## by Luke Confait

## Dataset

The data set contains information of 183,412 bike trips taken by users of the Ford GoBike bike sharing service during February 2019. The data includes information about the trip duration, the date and time when the trip takes place and the type of user in categories such as whether they are a subscriber or a customer. The dataset can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).

Some initial wrangling was performed to remove null values. A distance from start to end station feature was engineered from the data and the start and end time converted to start and end date and hour as well as day of week for the start of trips.

## Summary of Findings

The exploration found the Trip duration and distance from start to end station to be unimodal with a roughly normal distribution after transforming the data to a logarithmic scale. 

More trips were found to occur during the week compared with the weekend. The most frequent trips occured at the peak times for commuting to and from work idicating one of the primary use case of the service.

It was found that there was a linear trend in the minimum time to travel a certain distance from start to end station the correlation was fairly weak howe

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.