# Ford GoBike Data Investigation & Visualization
## by ADELEKE ADEKOLA EMMANUEL


## Dataset

The dataset, 201902-fordgobike-tripdata.csv, is downloaded from Udacity classroom and licensed by Ford GoBike. This dataset includes 183,411 trips with 16 features such as locations, time, and user attributes. There are start and end stations. I noticed that most trips happen on the same stations, so I subset the dataset by choosing top 5 trips start stations with the most trips.

## Dataset Tools

This project was done on a Jupyter notebook on a python machine. Using libraries such as;
>Pandas
>Numpy
>matplotlib.pyplot
>Seaborn
>Warning

## Summary of Findings

> Univariate Exploration: For the gender groups, the number of trips in male riders is 3 times more than the number of trips in females. It needs to be investigated more. Most of riders are 30 to 40 years old and the duration of trips is around 650 seconds.

> Bivariate Exploration: There is a slightly negative correlation between age and duration of trips. After separation the top 5 stations, Weekdays have the most trips than weekends. Trip Duration depends on the age of the member. Another observations is Start station and end station does not really affect the trip duration. There is correlation between duration and user type.

> Multivariate Exploration: The number of higher duration trip is higher for male but percentage is higher for women and other, also other has one more peak at nearly the age of 60 years for higher duration time.

## Key Insights for Presentation

The type of user has an influence on the use of this service. There are quite a lot of differences;

> Duration of use
Subscribers tends to have stable duration usage than Customers

> Days of use
Subscribers tends to use the service in weekdays, in contrast Customers have more flexible time.

> Hours of use
Subscribers have very intense usage at peak hour.


# REFERENCES

Github

Stackoverflow

Google

Kaggle

Slack


```python

```
