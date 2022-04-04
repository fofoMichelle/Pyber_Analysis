# Pyber_Analysis
## Overview of the Analysis
This analysis was conducted on the Pyber company which is a ride-sharing app company. We had two sets of data which was showing the ride data with locations and number of drivers and a second one with location and the fare for every ride. Our main goal was to compare each rides fare along with the number of drivers for each type of location (urban,rural,suburban) and create a clear visualization with the metplotib libray and provide recommendation to the CEO ideas on how to improve the access to ride-sharing services and determine the affordability for the undersed neiberhoods.
Our roadmap to execute the project included but was not limited to determinining the following points:
. The total number of rides for each city type.
. The average and total  fares for each city type.
. The total number of drivers for each city type
Now lets dive more into the results of the analysis and small summary on how the project was conducted.
## Results 
In order to perform the analysis, I merged datasets using left join based on the city column and got a one dataset with all available data.  I then created summary dataframe by city type.
This allowed to come up with the below results

***Total ride by city type***

- This summary shows that there is a high demand for Pyber in terms of rides in Urban cities compared to rural and suburban cities. The figure below demonstrates to which extend the rides in urban cities was high with 68.4% of rides originating from urban cities while suburban cities and rural cities only had a percentage of 26.3% and 5.3% respectively of the Pyber rides.

![image](https://user-images.githubusercontent.com/99924850/161457700-14d4398b-5280-47f6-ac89-69b713b1dc81.png)

***Total Fare by city type***
- The figure below shows the Total Fares in different type of cities, and we can clearly see that the urban cities had a high total fare compared to suburban and rural cities which is understandable given the fact that was a high demand of rides

![image](https://user-images.githubusercontent.com/99924850/161457617-33d10545-d86d-4de5-8092-c4aa95f491f0.png)

***Total drivers by city type***
- On the figure below we highlighted the number of drivers per city and as we would expect the total drivers in urban areas is higher than the suburban areas and rural areas given the fact that the demand in rides is higher 
- This is explained by the fact that the demand in services offered by Pyber is higher in urban cities, the supply had to be high as well.

![image](https://user-images.githubusercontent.com/99924850/161473569-01a1d643-55b7-4c3d-b67e-edc6a4982702.png)



***Pyber Summary of rides and fares***

- The figure below shows also the disparities in terms of cost and we can clearly see that the rural cities pay more per ride than urban cities with the average cost per ride being almost 10$ more in rural cities compared to urban cities

![image](https://user-images.githubusercontent.com/99924850/161457893-75fd5cab-be41-4549-8f64-fcfbcdc80042.png)

***Total fares,trends analysis***
- We took our analysis further than the simple observation of the effect of supply and demand on average cost per rides by analysing trends for a period of 4 months.    The figure below highlights our observation of the total fare being higher in urban areas than in suburban and rural areas, but it also shows trends of total fares in different types of cities. 
- One point to highlight on this figure is the peak in total fares around February in all cities which give us a room to analyze further on the reason behind that peak

![image](https://user-images.githubusercontent.com/99924850/161457444-4f780d5b-efc8-4ee7-81b6-2274a496b28a.png)
## Summary
. The first recommendation I would give to the Pyber CEO would be to look into reducing the number of drivers in urban areas; there are 2,405 drivers which made only 1,625 rides. That means not every driver has done at least one ride. They could be divided among suburban areas and rural areas this would reduce the disparities in terms of costs in different cities.
. Increasing the demand in rides in rural areas which could bring up the revenues in those areas as they seem to be more profitable this could be done by putting in place incentives to maintain loyal riders and drivers and attract new ones.
. A new analysis based on the last graph is needed this will help the company understand the reason why there was a peak in Febuary which help the company to come up with ideas on how to maintain the peak in the following months which in turns would increase the overall revenue 
