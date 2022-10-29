# FordGoBike-Data-Exploration
This project performs Data Exploration and Data Explanation on the Ford GoBike System dataset. It contains files for data visualizations of the main features and relationship between the features. It also contains a slide show file that presents the key insights of the main features of interest.

## Dataset

The Ford GoBike System Dataset includes information abdout individual rides made in a bike sharing system covering the greater San Francisco Bay area. The Dataset contains 183412 trip entries (rows) and 16 trip features (columns). The features include: (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). These features are classified into three broad areas namely:
1. Trip Duration
2. Station Information
3. Members' Personal Information


## Summary of Findings

In the course of this data exploration, many features of the dataset were explored in order to find the relationship between the features of the trip and the main features of interest (Bike Count and Trip Duration). 
    It was seen from the exploration that most bike riders are between the ages of 25 and 40 years. This age group represent the youths who could either be college students or employees and have a higher trip durations compared to the much younger bike riders and older ones.  
    It was observed that the peak hour with the highest bike riders is 5pm when most employees and students have closed from their day's activities. Another peak hour is recorded at 8am when most students are going to school and most employees are going to work. The trip distribution shows that within the early hours of 8am amd 9am and within the late hours of 5pm and 6pm, there are more bike riders who are subscribers compared to the customers.
    The visualization shows that over 87% of the bike riders are subscribers while the remaining 13% are customers. It can be seen that customers have higher trip durations compared to the subscribers. Customers' trips lasted for about 20-25 minutes while subscribers' trips lasted for about 10 minutes. This could mean that subcribers rent out bikes for official purposes while customers rent out bikes for fun or for business purposes such as delivery. 
    The exploration also shows that male riders are the majority bike riders with a count of 130651, followed by the female riders with a bike count of 40844, yet female riders have a longer trip duration compared to the male riders.
    The visualization shows that long trip durations are recorded during the weekends (Saturday and Sunday) while the peak count of bike riders is gotten on thursday.


## Key Insights for Presentation

For the presentation, more emphasis is laid on the main features of interest i.e the number of bike hired and the duration for the bike trips. Univariate barplots are used to illustrate the distribution of bike counts over some features in the dataset such as day of the week and hour of the day.
The features of the dataset that is related to the trip duration are also presented. These features include the user type, the gender, the age group of the bike riders and the day of ride. These plots communicates the relationship between the main features of interest and other features. A boxplot is used to illustrate the relationship between the member's gender and the trip duration. A barplot is presented to show the relationship between the user type of the members and the trip duration. A scatterplot is used to show the distribution of the trip duration over the members age groups.
A multivariate heatmap is presentd to show a breakdown of the number of bike riders during each hour of the day grouped according to the gender and type of user.
