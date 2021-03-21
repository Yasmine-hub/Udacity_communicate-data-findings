# Udacity Communicate Data Findings

# Ford GoBike System

### Yasmine Hussein
#### Mar- 2021

## Dataset
The data consist of approximately 183412 bike rides from FY2019. 16 variables, The attributes include the trip start/end time, start/end station, duration in seconds as well as additional information such as user type, gender, and birth date. 179K data points were removed from the analysis due to duplicates. The data can be found here, with feature documentation available here.

## Setup
In order to run the notebook, you'll need to install:

Python 3.6 Jupyter (notebook or lab)\ Pandas\ Numpy \ Matplotlib \ Seaborn

## Data wrangling
- Remove null records.
- Remove duplicates.
- Drop unneccessary variables.
- Adjust variables data type.
- Creating month and hour columns from start time column.

## Exploration
- Using code insights to explore data.
- Using Matplotlib and Seaborn to visualize the data.

## Summary 
In the exploration, I found that there are two types of clients using the system: subscribers who are mainly daily commuters, having short trips to and from work, who rent a bike on weekdays at 8-9am and 5-6pm, and, occasionally around the lunch time, and customers, usually tourists or occassional riders who use the system mainly on weekends to explore the Bay Area. The bike share system was used more often around summertime with a clear drop from January to March, most probably due to the weather condition. Moreover, I have checked if there are some differences in trends for genders. In most cases the trend for males/females was the same, except of the fact that females tend to have slightly longer trips and suprisingly, for casual users there are quite a lot of females using the system between January and March in comparison to males (the ratio is much smaller than for the rest of the year).

