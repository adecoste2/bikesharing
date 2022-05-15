# Bikesharing

## Project Overview 
After a trip to New York City, the clients want to institute a bike sharing business in their hometown of Des Moines, Iowa modeled after the CitiBike in NYC. At the request of key stakeholders a bike trip analysis was compiled addressing their main questions; which examines the length of time that bikes are checked out for all riders and genders, number of bike trips for all riders and genders for each hour of each day of the week and number of bike trips for each type of user and gender for each day of the week. 
Additional analysis was done to answer general business viability and risk management questions such as usage for loyalty members, top starting and ending locations, and bikes that are in need of repairs. 
The full analysis including storyboards can be found at [CitiBike_Analysis](https://public.tableau.com/app/profile/aimee.decoste/viz/CitiBike_Analysis_16520481624210/CitibikeAnalysis).


## Results
![Customers](https://github.com/adecoste2/bikesharing/blob/main/Images/Customers.png?raw=true)
Riders that have a subscription vs. riders that rent by the ride. The analysis shows that 81% of rides were by riders that are part of a loyalty program in the form of a subscription. This information can be used to further marketing campaigns. 


![Top_Starting_Locations](https://github.com/adecoste2/bikesharing/blob/main/Images/Top_Starting_Locations.png?raw=true)
Top starting locations show a correlative relationship between the concentration where a rider starts their ride and high populous areas (Midtown to Lower Manhattan). 


![Top_Ending_Locations](https://github.com/adecoste2/bikesharing/blob/main/Images/Top_Ending_Locations.png?raw=true)
Similar to top starting locations, top ending locations are also highly consentrated around the high populous areas of Midtown to Lower Manhattan. 

Both the Top starting and ending locations analysis shows information that is useful for product placement (bike rental and return hubs) planning. 

![Checkout_Times_For_Users](https://github.com/adecoste2/bikesharing/blob/main/Images/Checkout_Times_For_Users.png?raw=true)
Data shows that riders rent for shorter rides more frequently than longer rides with the majority of the rides being  2-15 minutes with a peak tripduration of 5 minutes. This analysis extrapolates on the results shown in the top starting and ending locations visualizations in that it demonstrates the consentration of uses are in high populous areas where the points between rider destinations are shorter in distance / duration. 

![Checkout_Times_For_Genders](https://github.com/adecoste2/bikesharing/blob/main/Images/Checkout_Times_For_Genders.png?raw=true)
A further analysis was done by breaking down the bike rental checkout times by gender, one can see that men make up the majority of riders. This insight can be used in marketing plans to further target both female and unknown genders.  

![Trips_by_Weekday_per_Hour](https://github.com/adecoste2/bikesharing/blob/main/Images/Trips_by_Weekday_per_Hour.png?raw=true)
The heatmap of trips by weekday per hour shows peaks in bike usage during traditional commuting times, 7am - 10am and  5pm to 8pm Monday to Friday with a slight decrease on Wednesday evening commute. Weekend trends show a more gradual use. Therefore, the information can be used to plan bike repairs in off-peak times. 

![Trips_by_Gender_Wkd_per_Hr](https://github.com/adecoste2/bikesharing/blob/main/Images/Trips_by_Gender_Wkd_per_Hr.png?raw=true)
A further breakdown of trips by gender by weekday per hour shows that male and female riders alike have the same peak user times. additionally, the denesity of use is  correlative to the gender use. 

![User_Trips_by_Gender_by_Weekday](https://github.com/adecoste2/bikesharing/blob/main/Images/User_Trips_by_Gender_by_Weekday.png?raw=true)
Further delving into the rental trends between genders and subscribers, it can be seen that the rider most likely to rent identifies as a Male Subscriber with a peak ride date of Thursday.  

![Bike_Repairs](https://github.com/adecoste2/bikesharing/blob/main/Images/Bike_Repairs.png?raw=true)
Bikes that are most likely to need repairs by referencing their id number with use count. This information in addition to the heatmap of trips per weekday per hour can be used to cross reference which bikes are in need of repairs and/or maintenance and when to schedule them. 


## Summary
Analyzed usage appears to be specific to the traits of New York City or a major metropolitan area where public or shared transportation is part of the infrastructure. 
Additional visualization considerations to scale the NYC CitiBike data for Des Moines may include:

* A heatmap of public transportation usage.
* A symbol map of high populous areas in Des Moines for bike rental/drop off hubs. 
