# Bikesharing

## Overview of Project
Citi Bikes in New York are very popular. Last time me and Kate had byked everywhere which allowed me to really get to know the city. Wanted to implement the same idea in my hometown of Des Monis. Kate has a potential angel investor who might be interested in providing seed funding to explore a bike sharing program in Des Monis. Citi Bike data released to the public for analysis but I need to be cautious when looking at the data, as it applies specifically to New York City, Des Moines is quite different. I downloaded data from August because there is likely more traffic during the summer months. 

### Tools and technologies used:

1. Jupyter Notebook 

2. Tableau

   * Work sheets
   
   * Dashboards
   
   * Stories 

## Analysis Results: 

1. Analyzed the downloaded data and observed the trip duration column containing invalid date and time.  

![Screenshot 2022-12-04 at 3 06 03 AM](https://user-images.githubusercontent.com/44387918/205487705-26c4bac6-5391-4479-9402-8c74b8d79ef5.png)

2. Converted trip duration column date and time using to_datetime() function.

![Screenshot 2022-12-04 at 3 06 14 AM](https://user-images.githubusercontent.com/44387918/205487717-9fee47fc-332e-4f39-ae87-bcea632f2cd9.png)

3. Analyzed number of trips by duration 

![Screenshot 2022-12-04 at 2 29 06 AM](https://user-images.githubusercontent.com/44387918/205487740-53cee5d1-32f9-4799-b43a-cfef8a811ced.png)

4. Trips by duration and gender. Observed Male riders are more. 

![Screenshot 2022-12-04 at 2 29 19 AM](https://user-images.githubusercontent.com/44387918/205487771-aa8d3668-c1b5-43be-8526-657bc47ccd76.png)

5. Trips by weekday per hour. 

    * Saturday / Sunday busy times: **9AM to 7PM**
    
    * Weekdays busy times: **7 to 9AM & 4 to 8PM** 

![Screenshot 2022-12-04 at 2 29 27 AM](https://user-images.githubusercontent.com/44387918/205487777-7ae81b2d-ea17-4d3c-b4bd-2b7bcbd088c0.png)

6. Trips by Gender / weekday per hour 

![Screenshot 2022-12-04 at 2 29 40 AM](https://user-images.githubusercontent.com/44387918/205487839-3597d8de-440d-455b-ae25-b2343373e643.png)

7. Trips by user type, weekday and Gender 

![Screenshot 2022-12-05 at 9 56 16 PM](https://user-images.githubusercontent.com/44387918/205831821-b84e51a9-da91-4a80-a7d5-8d0d0f2411b4.png)

8. Gender by Location

![Screenshot 2022-12-04 at 2 29 58 AM](https://user-images.githubusercontent.com/44387918/205487901-32e675b8-c81a-40f0-af74-c2ee8ee559a3.png)

9. User type by birth year. 

![Screenshot 2022-12-04 at 2 30 10 AM](https://user-images.githubusercontent.com/44387918/205487906-2ff4d779-c772-47b9-8574-853d1e0bbf4e.png)


### Link to Tableau dashboard:  https://public.tableau.com/app/profile/varun.yalaka/viz/NYCCitybikesharingAnalysis/Story1?publish=yes 

## Summary

After analyzing New York city data, bikes are very busy on weekends and morning and evening times on weekdays. Lot of male riders are subscribed, after analysis stats it works for Des Monis as well.
