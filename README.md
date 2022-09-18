# bikesharing
## Overview
The purpose of this analysis is to provide a business proposal that shows a bike trip analysis. In this analysis I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype I'll create a set of visualizations to:
* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

Lastly I'll add these new visualizations to the two I created in the module for my final presentation.

## Tableaue Public Link
https://public.tableau.com/views/NYCBike_16635330527970/NYCCitiBikeAnalysisChallenge?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Results
![Checkout Times for Users](https://user-images.githubusercontent.com/105949411/190929551-1dd889a4-a107-4906-abe4-9b030ca36e9d.png)

A line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.

![Checkout Times by Gender](https://user-images.githubusercontent.com/105949411/190929558-32cd19ed-a637-4778-964c-c77ac7a9d9d2.png)

A line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.

![Trips by Weekday per Hour](https://user-images.githubusercontent.com/105949411/190929578-24a3db60-dc79-44ab-bd7c-975b2abe5260.png)

A heatmap is showing the number of bike trips for each hour of each day of the week.

![Trips by Gender Weekday per Hour](https://user-images.githubusercontent.com/105949411/190929587-03fc5509-8077-4088-9e72-9da4c51481a4.png)

A heatmap is showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.

![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/105949411/190929600-c9fd548c-ecdd-46bc-af8d-63835f6ec0a0.png)

A heatmap is showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

![Customer Description](https://user-images.githubusercontent.com/105949411/190929610-c005ace0-3d13-4ce1-8b81-fd6d2f9debeb.png)

The graph on the left shows that most people using the bike sharing service are active subscribers. The graph on the right shows that males are by far the majority users of the service.

![Top Ending Location](https://user-images.githubusercontent.com/105949411/190929723-254ec40d-41de-4d70-a180-a7b174894534.png)

This graph shows the top ending locations for the bike sharing service.

## Summary
The NYC Bikesharing data showed:
* Subscribers were the primary users
* Most users were men
* Most trips were under 10 min long
* 5-10am and 3-8pm had the most riders
* Midtown and Downtown had the most use
 
In summation a bike sharing program could work in Des Moines, IA but it would need to more in more densly populated areas of the city where there is less available parking. However, some additional information should also be gathered to help design a bikesharing program for Des Moines, IA.
* A graph showing the morning and evening commuter traffic to see where rideres are traveling from and to.
* Gather more demographic data about the riders themselves to further narrow down what groups are using the bikesharing most.
