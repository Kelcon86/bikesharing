# Bikesharing

## Overview
After using CitiBike to get around New York City during a trip, I created a presentation using Tableau to try to convince investors that a bike-sharing program in Des Moines is a solid business proposal. 

Here's my Tableau link https://public.tableau.com/app/profile/kelly.c3248/viz/BikesharingCitiBikeNYCAugust2019/CitiBikeAugustinNY?publish=yes

## Results

<img width="1045" alt="Checkout_Times_Users_Image" src="https://user-images.githubusercontent.com/60076980/161429751-9f53b1b9-72f7-41e8-821f-f52423f984fc.png">
Using the tripduration broken down by hour and minute on the x axis and the count of bikes on the y axis, we can see the duration times for users in August 2019. The peak trip duration was just 5 minutes and the vast majority of trips were under 20 minutes.  


<img width="1028" alt="Checkout_Times_Gender_Image" src="https://user-images.githubusercontent.com/60076980/161429764-c8d877b3-f717-49fd-9906-051322a2790f.png">
Using the same x and y axis as the previous graph, I added gender to the color and filter fields to see how gender affected the trip duration. While we could see that there were far more male users, the trip duration remained short (5-6 minutes) for all users.  



<img width="521" alt="Trips_Weekday_per_hour" src="https://user-images.githubusercontent.com/60076980/161443521-1c5f1913-bb38-4057-8822-0a1ead96da6b.png">
The graph above shows the trips broken down by weekday and hour, which shows that 8 AM and 5-7 PM are the most popular times to rent a CitiBike. This is consistent with riders using the CitiBikes for commuting to and from work.


<img width="1061" alt="Trips_Gender_Weekday_Hour" src="https://user-images.githubusercontent.com/60076980/161443527-98a1a492-b37c-4739-9567-ebb01b0b662c.png">
Using a heatmap, I graphed the count of trips broken down by weekday, hour and gender. Amongst both genders 8 AM and 5-7 PM were the peak times for rides, which is consistent with the commuter theory mentioned previously. 



<img width="1064" alt="User_Trips_Gender_Weekday" src="https://user-images.githubusercontent.com/60076980/161429776-01778e05-77af-4edf-a557-404dd2e4f00c.png">
The graph above shows the user trips broken down by gender and weekday. We can see on the heatmap that the majority of users are subscribers and that there are more male users than female or unknown. The most popular days for trips was Thursday and Friday for subscribers and Saturday and Sunday for customers. 



<img width="1010" alt="August_Peak_Hours" src="https://user-images.githubusercontent.com/60076980/161441336-91fe390b-8e2b-4f69-84cf-7e1cda07f6dc.png">
Using a horizontal bar chart I graphed the peak hours for rides in August 2019, showing that the hours of 5-7 PM were the most popular time to ride. 



<img width="1058" alt="Top_Ending_Locations_Image" src="https://user-images.githubusercontent.com/60076980/161429786-9413bb62-7e2b-4237-96b1-68b30926794e.png">
Using a symbal map we can see the top ending ride locations. By dropping the count of rides into the color and size filters, we are able to see that some of the most popular ending locations are along the Hudson River Greenway, a bike trail with water views. 

## Summary
Analyzing CitiBike data from August 2019 in NYC allowed me to visualize several important factors when determining if CitiBike would work well in Des Moines. The first thing I analyzed was the trip duration times for users. I was surprised to find that most trips were under 20 minutes long. This leads me to believe that most people are only using the bikes to get from point A to point B and aren't using them as much for leisure rides. I then broke down the trip duration by gender and found that males were more than twice as likely to use the CitiBikes as females were. This data can be used to try to find different ways to market the CitiBikes in order to interest more females to ride. After breaking down the user trips by weekday, we found that the majority of users were subscribers of CitiBike and that Thursdays and Fridays were the most common days for rides. The most common days for non-subscribing customers was Saturday and Sunday, leading me to believe that those customers were possibly from out of town and just visiting the city for the weekend. While analyzing the start times by weekday and hour we found that regardless of gender the most common start times were 8 AM and 5-7 PM, which would be consistent with commuters. The last graph shows the top ending locations. A large percentage of the most popular ending locations were along the Hudson River Greenway, a bike trail with water views. 

While Des Moines doesn't get nearly as many tourists as New York City, the data has shown that many of the repeat users are likely using the CitiBikes to commute to and from work or for other short trips. It will be important to look at the bike trails that Des Moines has in place as those will be a big factor in CitiBikes success in that location.

Two additional visualizations that I would perform with the given dataset are to use the birth year, gender and usertype to determine which age group and gender are most likely to subscribe to CitiBike and using the birth year and start time to determine if a certain age group is more likely to utilize the CitiBikes at certain hours.

