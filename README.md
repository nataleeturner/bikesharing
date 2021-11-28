# NYC Bike Sharing Analysis

## Purpose

The purpose of this analysis is to convince investors that implementing a bike sharing program in Des Moines would be a good investment. In order to make this case, I used Tableau to create several meaningful visualizations to present to the investors. These visualizations were created using the CitiBike data for the month of August in 2019 in New York City.

## Results

### Checkout Times for Users

<img width="1004" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/88349443/143782040-678e5b82-9ce5-4dd0-abca-903743f0d508.png">

This graph shows a trend of how many bikes are checked out for each total checkout time. The peak total checkout time is around 4-7 minutes. After 7 minutes the average trip duration drops significantly until 45 min trips, where it starts to plateau. After 45 minutes, the number of rides slowly approaches zero. This means that most trips are relatively short, and the bikes generally aren’t used to go very long distances. 

### Checkout Times by Gender

<img width="1008" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/88349443/143782045-e76ca1a7-5ccb-4bae-a0ff-2aa7cc505a68.png">

While this graph looks much like the first, the number of rides at each trip duration is broken down by gender. The major point in this graph is that there are far more male riders than female riders. Female riders make up only about 25% of the total ridership. The graph for males is very similar to the overall graph, with the peak trip duration being 4-7 minutes, while the female graph is slightly more elongated at the peak, with the peak trip duration being 4 -9 minutes. Additionally, the female graph shows a slower decline in total rides per trip duration until about 28 minutes, where it drops quicker and slowly approaches zero. 

This shows that, on average, female bike share users tend to take longer trips. Whether they are riding longer distances or just at slower speed than their male counterparts should be investigated further as this cannot be determined from this graph. 

Lastly, the trips for people whose gender is unknown shows that the peak trip duration ranges from 5 to 28 minutes. There is not much that can be deduced from this information other than people that tend to not include their gender information take longer rides.

### Trips by Weekday per Hour

<img width="1010" alt="Trips Weekday per Hour" src="https://user-images.githubusercontent.com/88349443/143782060-af8e1d52-f8b1-470e-8254-1f610ad9ac68.png">

The chart above is a heat map of the number of rides that start during each hour of the day for each day of the week. The darker red the square, the more rides that are starting in that hour block. 

From this chart, we can infer that most rides are taken by people going to and from work. Most workdays are Monday – Friday, start around 7-9AM and end around 5-7PM. The blocks for these hours during the week are the darkest red. 

The second most significant piece of information we can gather from this chart is that there are a significant number of riders that use the bikes all throughout the weekend. This would most likely be due to tourists visiting NYC and using the bikes as an easy way to get around the city. The heat map shows that there are some tourists arriving on Thursday and each day gets darker through Saturday, with a drop off on Sunday and again on Monday when most tourists are likely returning home.

If Des Moines is a city where people live within a 10-minute bike ride from their place of occupation, and/or if it’s a city with tourists that can easily bike from tourist attraction to tourist attraction, then implementing a bike sharing program could be a valuable business.

### Trips by Gender (Weekday per Hour)

<img width="1008" alt="Trips Gender Weekday per Hour" src="https://user-images.githubusercontent.com/88349443/143782070-f07e48f9-1da6-4253-b516-a01f7273d007.png">

This chart breaks down the previous chart’s data into gender. You can see that female and male riders tend to use the bikes for the same reasons. Both charts are almost identical, but the female chart has lighter colors since there are fewer total riders compared to males.

### User Trips by Gender by Weekday

<img width="1002" alt="Trips Gender Weekday" src="https://user-images.githubusercontent.com/88349443/143782071-65229c40-3192-41bf-8d7d-bd2b4c25aa80.png">

This chart breaks up the total usage per day by gender and by user type (subscribers vs non-subscribers). First, you can tell from this chart that there are far more users that are subscribers than there are non-subscribers. Second, the subscribers are likely the locals using the bikes during the week to go to and from work since there are more rides by subscribers on weekdays than there are on weekends. Alternatively, the non-subscribers are more likely to be the tourists that have just come into the city to visit on the weekend. As you can see, they ride more on the weekends (Friday-Sunday) than they do on weekdays (Monday-Thursday).

### Bike Repairs

<img width="1003" alt="Bike Repairs" src="https://user-images.githubusercontent.com/88349443/143782077-6a061817-105b-4b15-ace2-e693dfc114bd.png">

This chart is a good representation of how you can determine what bikes need servicing. The color and size of the square shows how many rides have been taken on each bike, with the darker and larger square being the bike with more rides. The one piece of information that would be valuable to further analyze this graph would be to understand the average number of rides for which a bike will require maintenance. That way, I could show the investors how many bikes may need maintenance each month.

### Top Starting Locations

<img width="1010" alt="Starting Locations" src="https://user-images.githubusercontent.com/88349443/143782084-f9e572e4-c5af-4fa9-8db6-96e3a2508a65.png">

This graph shows the top starting locations for CitiBike rides in New York City. The larger and darker the circle, the more rides that began in that general area. Some further investigation should yield confirm for us whether the most popular starting locations are in residential areas, for riders hopping on a bike to get to work, in commercial areas, for riders coming home from work, or near tourist attractions, for riders using the bikes to tour the city. This visualization is a good tool to use when determining the optimal areas in Des Moines to house the bikes. 

## Summary

In conclusion, establishing a bike sharing program in Des Moines would be a solid business investment if it’s a city where people live within a 10 minute or less bike ride from their office or if there are a decent amount of tourists. If Des Moines meets either of these qualifications, the bikes can be placed strategically throughout the city to optimize adoption of this program.

Some important points to consider based on the visualizations of our data set are that locals primarily use the bikes on weekdays to get to/from work and by tourists on weekends to tour around the city. Additionally, males are 3 times as likely to use bikes as females, but they both use them for the same reasons. Lastly, it’s important to sell subscriptions to the service as this group uses the bike service the most.

One visualization that would add to this analysis is to group the customers into 5- or 10-year age groups and graph the total number of rides per age group. This would give a better indication as to what ages are most likely to use the bike share program and could allow for improved optimization of the placement of bikes (areas of town, apartments vs neighborhoods, etc.). 

A second visualization that would be beneficial to include in the analysis is to use the same age groups as the previous proposal, and then break the ride data up by the number of trips per day for each hour of the day. Similar to visualizations 3-5 but broken up by age group. This will give even more information about the trends of various age groups.
