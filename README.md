# PyBear_Analysis
## Overview
Ride sharing is a relatively new trend in which owners of privately owned vehicles are contracted to provide rides to passengers for a fee.  This analysis looks at data 3 different types of cities, urban, suburban, and rural to examine the following data for each city type:
  - Total number of rides 
  - Total number of drivers
  - Total fares
  - Average fare per ride, and 
  - Average fare per driver 

This report analyzes how these different pieces of data differ by each city type, and makes recommendations about how these results can be used to inform decisions for the ride sharing platform. 


## Results
For each of the city types in the first quarter of 2019, the total number of rides, total number of drivers, total fares, average fare per ride, and average fare per driver can be summarized in the following table:

![summary_df](https://user-images.githubusercontent.com/106559768/180072610-03826300-16ff-4df2-8384-1b1413436cdd.png)

In this analysis, the first major consideration is the city types themselves. Different types of cities are going to have different population densities and infrastructure, which directly impact the demand for ride share services. A large, or urban city is going to have a larger population. More people, closer together might make it more difficult to own a vehicle for reasons like regular difficulty finding a parking spot, time limits on parking, parking fees, and general traffic. The demand for transportation services in an urban city might differ compared to a rural city where the infrastructure is more spread out. Owning a vehicle in a rural city might be more of a necessity when the grocery store is 10 miles away and the public bus only comes once per hour. Additionally, being a driver in the rural city might not seem too lucrative if there is very little demand for riders. The suburban city type is somewhere in the middle; suburban cities have an intermediate population size, and tend to encompas residential neighborhoods. Based on an intermediate population size and spread of the infastructure, the probability that someone is going to need a ride on any given day is fairly high. 

The hypothesis that population density and infrastructure of different city types impact ride sharing is supported by information in the summary table. In total, the number of rides in urban cities is 13 times the total number of rides for rural cities. The summary table also shows there are 30 times more drivers to meet this demand. This information can be further broken down and visualized using the following graph:

![Screenshot (32)](https://user-images.githubusercontent.com/106559768/180071526-c8bf6924-8b1a-44d9-bc3c-3ac0ef007afb.png)

In this graph, each dot represents a different city, and the size of the dot correlates with the number of drivers. There is a positive correlation between the total number of rides and the total number of drivers, meaning as the city type increases in size, the demand for rides increases.  Additionally as the number of rides increase the size of the circle increases, indicating the number of drivers also increases. 

This chart also visualizes another trend with the average fare per ride. As the demand for rides increase, the cost of the fare decreases. The summary table shows as the need for drivers increases in urban setting, there is more competition; in an urban setting, there are more drivers than riders, which drives the average cost of fare as well as the driver wages down. Inversely, in a rural setting where there is less demand for drivers, the cost of fare is higher, and the few drivers who elect to accept passengers earn more on average. The suburban market is fairly balanced in the middle; there is slightly more demand for rides than drivers which drives the price of the average fare up, and the results is more favorable wage for the drivers. 

The summary table also considers the ammount of total fares; The following graph visualizes the those total fares as percentages. 

![Screenshot (33)](https://user-images.githubusercontent.com/106559768/180072682-abb59c1a-7ebd-4848-a230-5a748b81f52c.png) 

In total, the urban city types generate 20% more revenue than the rural and suburban city types combined. 

The total fares can also be visualized over time using the following graph

![Pyber_fare_summary](https://user-images.githubusercontent.com/106559768/180072842-a6d9401f-b43d-46ce-962d-b7d0a6d07f00.png) 

On a grand scale, the slopes of all of the city types remain relatively flat, implying buisness has been steady in all city types. Taking a closer look at the individual city types, The rural city type fluxuated the least. Rural total fares consistently averaged below $500 per day. 

Suburban cities are the second largest city type, and generated the second highest total fares by city type. In general, the total fare fluxuated around $1000 per day. 

the trend of the urban line shows that urban cities consistently bring in the highes total fares. Urban cities also show the most growth. Looking at how the line progresses, the line trends steadily upwards in the first 2 months, and even though the line fluxuates during March, the overall total revenue in the last 3 months averages more than the starting month.




## Summary
Based on the information gathered, I would make the recommendations:

1.	**Focus more effort into marketing for suburban city types**. The peak in the ride share faes in February might indicate people were utilizing the ride service for convenience rather than necessity. Campaigns about conveniently accessing leisure activities, like shopping at a nearby mall, getting home safely after having a few cocktails, or even taking a weekend trip to a nearby urban city might be effective marketing campaigns.

2.	**Incentivize riders in rural cities**. Perhaps a lack of engagement in the rural cities is in part due to people in small cities not knowing that ride sharing is available.  One way to stimulate interest in ride sharing is to offer a discount on the service. This would encourage people to get familiar with the ride sharing platform and try it out.  

3.	**Adjust for the number of drivers in large cities**. The supply of drivers is significantly more than the demand of the rides, so there are a couple of options to consider. First, the number of drivers could be reduced. With fewer drivers, the average wages per driver would increase and the remaining drivers would continue to meet the demand. Another option is to drive more demand. Because the customer base in urban cities is firmly established, a discount promotion that offers riders a discount for referring their friends could be an inticing offer for many regular riders. 

