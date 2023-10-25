# Tableau-Analysis
CitiBike Locations Analysis using Tableau
In this read me the link to the Tableau workbook and the file itself are contained
https://public.tableau.com/app/profile/marshal.rockafellow/viz/CitiBikeAnalysis_16982684391460/SummaryDashboard?


## Summary of the Workbook
In this tableau workbook I used multipl graphs to focus primarily on the different branches/locations of the citibikes. 
All 4 of the visulizations are labeled with the location in it. 
The data is from the whole year of 2022 all grouped in 1 union.
This data due to being on Tableau pulic was filtered to only show for Electronic Bikes.

### Visulization 1: Popular Locations
This visulization is the most basic as it takes the start location names and the end location bnames and gives the total count for  each. 
This was done and then sorted by decending so the main focus right of the bat can be on the most popular locations.
This could be as simple as these are the locations to add more elctic bikes to.

### Visulization 2: Ride Length 
This visulization is again focused on the different citibike locations. 
Here it is broken down into minutes with each stations total ride duration.
This is done by taking the start ride time and end ride time with the DATEDIFF function to get the new measurment.
Here we can see if the most popular locations correspond with the most ride minutes. 

### Visulization 3: Members
This visulization is again focused on the different citibike locations. 
In this visulization we compare the traffic at each location by members or common users. 
This is particularly useful if trying to increase membership share and could focus on largest stations with least members.
In order to get this data a custom set had to be made.
In means they are members and out means they are not.

### Visulization 4: Map
This visulization is again focused on the different citibike locations. 
This visulization differs by focusing on the geographic side of things. 
The map displays the total count of rides per station. 
This is easily displayed with a color code that has red for the lowest traffic and green for the highest. 
This can show if a certain location is low or the geographic region as a whole. 

### Dashboard
This dashboard summarizes all of the visulizations in one section in a strategic order. 
We start with visulization 1 so you may selct one of the most popular locations. 
From here we may find that location on the map to compare gegrapic locations in the area. 
Lastly we can focus on the member ratio and the total minutes used. 

## Analysis
- The regional analysis done on visulization 4 shows that the most used locations are not in a speific geogpahical region but rather spead all throughout the city
- Using visulization 3 we are able to identify that 6 in the top 30 most used locations have a large amount of non-members use
- Using visulization 1 and 2 we can conclude that highr ride minutes actual does not correlate with the most populare locations but actually the most popular locations thrive on shorter rides
- When combining all of this data into one large summary it is clear that other factors play a larger role on what make the location the most popular
-   Further testing would include population density per region, workforce members per region, car owners in the city, etc. to give us a better understanding
