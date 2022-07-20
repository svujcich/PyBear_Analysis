# PyBear_Analysis
## Overview
Ride sharing is a relatively new trend in which a owners of privately owned vehicles are contracted to provide rides to passengers for a fee.  This analysis looks at data 3 different types of cities, urban, suburban, and rural to examine the following data for each city type:
  - Total number of rides 
  - Total number of drivers
  - Total fares
  - Average fare per ride, and 
  - Average fare per driver 

This report analyzes how these different pieces of data differ by each city type, and makes recommendations about how these results can be used to inform decisions for the ride sharing platform. 


## Results
For each of the city types in the first quarter of 2019, the total number of rides, total number of drivers, total fares, average fare per ride, and average fare per driver can be summarized in the following table:

![summary_df](https://user-images.githubusercontent.com/106559768/180072610-03826300-16ff-4df2-8384-1b1413436cdd.png)

In this analysis, the first major consideration is the city types themselves. Different types of cities are going to have different population densities and infrastructure, which directly impact the demand for ride share services. Take a large city for example. A large city is going to have a larger population. More people closer together might make it more difficult to own a vehicle for reasons like regular difficulty in finding a parking spot, time limits on parking, parking fees, and general traffic. The demand for transportation services in a big city might differ drastically compared to a rural city where the infrastructure is more spread out. Owning a vehicle in a rural city might be more of a necessity when the grocery store is 10 miles away and the public bus only comes once per hour. Additionally, being a driver in the rural city might not seem too lucrative if there is very little demand for rides. The suburban city type is somewhere in the middle; suburban cities have an intermediate population size, and infrastructure distribution, and based on the population size, the probability that someone is going to need a ride is fairly high. 

The impact of population density and infrastructure of different city types are supported by information in the summary table. In total, the number of rides in urban cities is 13 times the total number of rides for rural cities. Additionally, we see there are 30 times more drivers to meet this demand. This information can be further broken down and visualized using the following graph:

![Screenshot (32)](https://user-images.githubusercontent.com/106559768/180071526-c8bf6924-8b1a-44d9-bc3c-3ac0ef007afb.png)

In this graph, each dot represents a different city, and the size of the dot correlates with the number of drivers. There is a positive correlation between the total number of rides and the total number of drivers. As the city type increases in size, the demand for rides increases, and the number of drivers also increases. 
This chart also visualizes another trend with the average fare per ride. As the demand for rides increase, the cost of the fare decreases. This trend can be analyzed further using information about fare per driver. The summary table shows as the need for drivers increases in urban setting, there is more competition; in an urban setting, there are more drivers than riders which drives the average cost of fare as well as the driver wages down. Inversely in a rural setting where there is very little demand for drivers, the cost of fare is higher, and few drivers who elect to accept passengers on average earn more. The suburban market is fairly balanced in the middle; there is slightly more demand for rides than drivers which drives the price of the average fare up, and the results in a more favorable wage for the drivers. 

The final consideration is the total fares. The summary table shows the total the most profitable city type for ride sharing is the urban city type. The following graph visualizes the total fares as percentages. 

![Screenshot (33)](https://user-images.githubusercontent.com/106559768/180072682-abb59c1a-7ebd-4848-a230-5a748b81f52c.png)

In total, the urban city types generate about 20% more revenue than the rural and suburban city types combined. 
The total fares can also be visualized over time in the following graph

![Pyber_fare_summary](https://user-images.githubusercontent.com/106559768/180072842-a6d9401f-b43d-46ce-962d-b7d0a6d07f00.png)


Over the first quarter, urban ride share revenue averaged between $2000 - $2500. This might suggest there are regular customers. Although the month of January was slightly below this this average, the ride share trends in a positive direction over the duration of the quarter. Inversely the rural city types the total fare consistently averaged below $500. Finally, The total fares for Suburban city types fluxuate around $1000.


## Summary
Based on the information gathered, I would make the recommendations:

1.	**Focus more effort into marketing for suburban city types**. Since the total fare by month fluxuates, people might be utilizing the ride service for convenience rather than necessity. Campaigns about conveniently accessing leisure activities or getting home safely after having a few cocktails might prove to be effective.

2.	**incentivize riders in rural cities**. Perhaps a lack of engagement in the rural cities is in part due to people in small cities not knowing that ride sharing is available.  One way to stimulate interest in ride sharing is to offer a discount on the service. This would encourage people to get familiar with the ride sharing platform, and try it out.  

3.	**Reduce the number of drivers in large cities**. The supply of drivers is significantly more than the demand of the rides. Reducing the number of drivers would increase the average fare per driver to earn a more livable wage. 


