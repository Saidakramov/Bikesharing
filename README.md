# Bikesharing1
# Bikesharing

## Overview of the statistical analysis:

- For this analysis, we used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, we created a set of visualizations to:
  - Show the length of time that bikes are checked out for all riders and genders.
  - Show the number of bike trips for all riders and genders for each hour of each day of the week.
  - Show the number of bike trips for each type of user and gender for each day of the week.
- Finally, we added these new visualizations to the two we created in this module for our final presentation and analysis to pitch to investors.
- [Link to dashborad](https://public.tableau.com/app/profile/akbar5210/viz/BikesharingDeliverable3/Deliverable3)

## Results:
- Checkout time for users:
<img width="1038" alt="Chekout time for usrs" src="https://user-images.githubusercontent.com/89552059/192167520-4045486f-8f60-489d-8517-dc77e41248f8.png">
- We can see that most rides are used for about an hour. The peak is 146,752 bikes at 5 minutes and 1122 bikes at 59 minutes.

- Checkout time by gender:
<img width="1045" alt="Checkout time by gender" src="https://user-images.githubusercontent.com/89552059/192167529-8719ef6b-fc2d-49db-abdb-62911ed85da0.png">
- This graph displays the ratio of genders. We notice that male riders are about three times more than female riders. Males peaked at 108,087 bikes at 5 minutes, while females had 34,151 cycles at 6 minutes.

- Trips by weekday per hour:
<img width="1041" alt="Trips by weekday per hour" src="https://user-images.githubusercontent.com/89552059/192167532-c0a9ef25-368f-416a-8b27-3a08f225cb1d.png">
- It is primarily busy on weekdays from 6 to 9 am and 4-8 pm. But weekends are active from 10 am to 8 pm.

- Trips by gender by weekday per hour:
<img width="1039" alt="Trips by Gender" src="https://user-images.githubusercontent.com/89552059/192167535-d68a5c10-d38c-4d12-9cce-e475035182a7.png">
- Both genders show a similar pattern of renting. However, male renters exceed females multiple times.

- User trips by gender by weekday:
<img width="1044" alt="User trips by gender by weekday" src="https://user-images.githubusercontent.com/89552059/192167546-6adc2676-5151-4079-b84f-14f552e96941.png">
- Male subscribers rent over 200,000 bikes on Tuesdays, Thursdays, and Fridays. Female subscribers showed more activity on Tuesday, Friday and Saturday. For regular customers, most busy days appear to be Saturdays for females, males, and unknown.

- Dashboard:
<img width="1019" alt="Dashboard" src="https://user-images.githubusercontent.com/89552059/192167549-67502905-6d78-463f-98a3-41ae88e910f2.png">
- Here, we have multiple worksheets. We can see that the average trip duration is higher for younger riders, annual subscribers are significantly more than the short-term customers, the male ratio is higher than the females, and starting and ending locations are within the same area.


- August peak hours:
<img width="1010" alt="Peak Hours" src="https://user-images.githubusercontent.com/89552059/192167552-2bd026c2-fa83-4bf3-9155-6aaad67f600a.png">
- This graph shows peak renting hours, and we can notice that 0 to 5 am could be the best repair time.

## Summary:
- In general, we can notice that there are more male customers compared to female customers. Peak hours are during work start and work end hours during weekdays and the whole day during weekends. We can peek times between 0 to 5 am to perform bike repairs. Out of 2,344,244 rides, 1,900,359 rides are from annual subscribers. 
- We could find and include weather data analysis to see how rainy and cold days affect the study.
- We could include data throughout the year to have a better picture. 
