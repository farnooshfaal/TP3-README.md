# TP3-README.md

Widget Uses and Experience Purpose:

The User will utilize the dashboard to answer their questions related to: 
1.	The Census Tracts containing the largest counts of crimes in 2019 and 2020
2.	The Census Tracts with the largest to smallest differences in crimes between the two years
3.	The trendlines between average income and theft rates
4.	Averaging these variables by the spatial filter of the map extent as the user pans through the neighbourhood census tracts

Dashboard Indicators: 

Top Left – Allows the user to see the Progression of theft counts with the ascending values of average income by census tracts within the map extent.
The purpose of this dashboard indicator is to help users understand whether there is a relationship between income and theft in the areas displayed on the map.  If the graph shows a clear trend of increased theft counts as average income decreases,this could suggest that poverty and crime are correlated in the area.

![Picture1](https://user-images.githubusercontent.com/55294090/231171336-cc36bf6b-90be-4f81-99ca-5e268ae98e26.png)

Bottom Left – Allows the user to see the average income between all census tracts within the map extent in relation to the census tracts with the highest average income.The purpose of this dashboard indicator is to provide users with a quick overview of the income distribution within the selected area. By comparing the average income of all census tracts to the highest income census tracts, users can gain insights into income inequality and the economic disparities that may exist within the area.

![Picture2](https://user-images.githubusercontent.com/55294090/231174129-6195803c-8584-45d9-8819-f7898a44d0a6.png)

Top and Bottom Right – Gauges to show the averaged thefts for the census tracts within the user’s dashboard view extent - compares between 2019 and 2020.
The purpose of these dashboard indicators is to provide users with a quick overview of how theft rates have changed between 2019 and 2020 within the selected area. The gauges allow users to see at a glance whether theft rates have increased, decreased, or remained relatively stable over time.

![Picture3](https://user-images.githubusercontent.com/55294090/231175975-cc89b981-5de7-439a-a5cf-053d6ce90bee.png)


Experience widgets: 
Map widget showing Web Scene visualizing census tracks by extruding attribute value (average income) to show proportions of average income differences across the neighbourhood with clickable census blocks showing pop-ups detailing individual census tract average income and thefts in 2019 and 2020, respectively. 
You can swap between the 3d average income map and the 2d crime difference ratio map and an animation between the two with the legend swapping as well can give the user a better spatial sense of the crime increases, decreases, totals and averages while interacting with the dashboard maps, gauges and indicators. 

The blueprint and makeup of this dashboard can be relevant to global cities with similar crime and income rates, as it provides a comprehensive and interactive way of exploring the relationship between these two variables. By using a combination of maps, gauges, and indicators, this dashboard enables users to easily compare and contrast theft rates across different census tracts and time periods, while also providing insights into the socioeconomic factors that may be driving these trends.

Furthermore, the map widget in this dashboard utilizes a vector basemap for building outlines and raster basemap imagery with transparent vector census data, which allows for a more accurate and detailed representation of the neighborhood. This approach can be applied to other global cities with similar characteristics, providing a useful tool for policymakers, law enforcement, and community leaders to understand crime patterns and develop targeted interventions.

https://experience.arcgis.com/experience/f2bd59e3e05b4fae8ee8f686e85af04b
