# Ford GoBike Data Exploration
## by Amr Ali Dawoud


## Ford GoBike Dataset

This data set includes information about 183412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Before exploring the data, I removed the null values and the unrequired columns. I also converted the types of some columns and created new columns(age, start_hour).


## Summary of Findings:

In my exploration I found that the duration of the trip is inversely related to the age. The younger the user, the longer the trip. I also found that subscribers tend to have longer trips than customers while males tend to have shorter trips than females. Users who share the bike for all trip have shorter trips than those who don't. I also concluded that most of the start stations that are associated with the longest trips are also associated with the longest trips as end stations. In the same way, most of the start stations that are associated with the shortest trips are also associated with the shortest trips as end stations. I also managed to find the top 20 start and end stations that have the longest and shortest mean duration of the trip. I also found both the longest and shortest 20 trips from the start station to the end station.

Outside of the main variables of interest, most users are 20-40 years old. The most common periods of the day when trips are likely to start are 7-9 am and 4-6 pm. Most users in the dataset are subscribers, males and didn't share the bike for all trip. There is an inverse relationship between the age and sharing the bike sot that most users who share bikes are in the twenties of age. By the way, bike sharing occurs only by subscribers which is intuitive.



## Key Insights for Presentation

For the presentation, I focus on the effects of age, user type and gender on the duration of the trip. I start by showing the histograms of the duration of the trip- which is transformed on a logarithmic scale- and the age of the users followed by a scatter plot showing the relationship between the age of the user and the duration of the trip. Then, I show 2 transformed box plots between both the user type and the gender and the duration of the trip. For the multivariate analysis, I also present some faceted scatter plots about the effect of different variables on the relationship between the duration of the trips and age of the user. After that, I introduce 2 bar plots showing the longest and the shortest 20 trips from the start station to the end station. Finally, I show a bar plot about the distribution of the hours when the trips started.
