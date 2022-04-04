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

***Graph that show the total fares***

- The figure below shows the Total Fares in different type of cities, and we can clearly see that the urban cities had a high total fare compared to suburban and rural cities which is understandable given the fact that was a high demand of rides

![image](https://user-images.githubusercontent.com/99924850/161457444-4f780d5b-efc8-4ee7-81b6-2274a496b28a.png)

***Total Fare by city type***

![image](https://user-images.githubusercontent.com/99924850/161457617-33d10545-d86d-4de5-8092-c4aa95f491f0.png)

***Total ride by city type***

![image](https://user-images.githubusercontent.com/99924850/161457700-14d4398b-5280-47f6-ac89-69b713b1dc81.png)


***Pyber Summary of rides and fares***

![image](https://user-images.githubusercontent.com/99924850/161457893-75fd5cab-be41-4549-8f64-fcfbcdc80042.png)
