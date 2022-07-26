# BikeSharing
Citibike analysis by using Tableau visualization

## Overview of the Project.

There is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.
For this analysis, We used Pandas to change the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After we converted the "tripduration" column to a datetime dataytpe, we exported the DataFrame as a CSV file to use for the trip analysis and created the visualization by using Tableau.

### Link to Tableau public

[link to dashboard](https://public.tableau.com/app/profile/saba.amin/viz/Book1_16583428739990/Citibike_Story)

## Results:

 "tripduration" column to a datetime dataytpe

![image](https://user-images.githubusercontent.com/92646311/182053949-61996a11-afc8-48e5-8022-207ef051b544.png)

### We created a set of visualizations shuch as:  

- **Below the both graphs shows the length of time that bikes are checked out for all riders and genders**

This visualization indicates the length of time of every bike ride during the month of August  It shows the busy peek time is first 15 minutes.

<img width="938" alt="Screen Shot 2022-07-17 at 11 52 23 PM" src="https://user-images.githubusercontent.com/92646311/179442850-198d4a2a-4de2-4225-ade1-a67ea3739085.png">

 The breakdown of citibike riders by gender, where mostly  male riders used the ride. Secondly, female and then unknown.
<img width="950" alt="Screen Shot 2022-07-17 at 11 53 39 PM" src="https://user-images.githubusercontent.com/92646311/179442941-ef7d87f1-79ee-45ca-a212-4e2b77d430a7.png">

 - **The number of bike trips for all riders weekday per hour**
 
 
1. On weekdays citibike riders traffic peak commuting times are 5PM to 7PM, 
2.  Thursday is the most busy day, and morning time starts from 6AM to 9AM and the evening time starts from 4PM to &pm. 
3.  Saturday and sunday are also busy.
 
 <img width="960" alt="Screen Shot 2022-07-17 at 11 58 42 PM" src="https://user-images.githubusercontent.com/92646311/179443328-a977688e-369c-43e3-9afc-210da5f10cb0.png">


- **The number of bike trips for each type of user and gender weekday per hour.**

Male riders are more than women and unknown. Moreover Thursday is the most busy day of the week.

<img width="962" alt="image" src="https://user-images.githubusercontent.com/92646311/179443364-1d1a982b-21b4-4617-8a9d-c739907d7b61.png">

Male subscribers are more than women subscribers and unknown subscribers, and ride the citibike most.
<img width="959" alt="Screen Shot 2022-07-17 at 11 59 54 PM" src="https://user-images.githubusercontent.com/92646311/179443418-2890e1be-650f-4bd7-8179-2d1fdfe21fee.png">

## Summary of the results and two additional visualizations

The visualization indicates that there are more subscribers than customers(non_subscribers) which also means that they use the service long term.

![image](https://user-images.githubusercontent.com/92646311/179446337-9b073dbf-a03c-4561-9535-5d9f793e4e67.png)

### Riders most Starting and Ending locations

Both visualizations show top starting and ending locations, both locations are  in the populous areas.

![image](https://user-images.githubusercontent.com/92646311/179445764-b8549dfa-2659-4772-adb6-b03870fc7d5e.png)

![image](https://user-images.githubusercontent.com/92646311/179445829-d23c75a3-0771-47a8-8727-f5099cac032f.png)

We did and performed multiple visualizations to determine and identified the citibike peak demand hours, days, locations, users by gender, and type of customers. 
We can perform better analysis by using data from the last 3 years to the current year, also comparing data for different months to determine trends across the year.
Further we can perform analysis to see if there are locations that would be more apealing in the future. There would be other factors such as vacations , weather, age and distance from work and bike renting location.


