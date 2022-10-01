# :hotel:  CodeBasics Hospitality Challenge

## :muscle:   About the Challenge

This is the first challenge by CodeBasics team. 

Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands are losing its market share and revenue in the luxury/business hotels category. The managing director of the company wants to make use of Data Analytics to deal with this problem.

As a Data Analyst, you have to provide insights to the Revenue Team to regain market share and revenue.

## :books: About the Data

You are provided with 5 tables containing data from 3 months - May, June and July.
- dim_date :  contains date, month_name, week_number and day_type
- dim_hotels : contains property_id, property_name, category and city
- dim_rooms : contains room_id and room_type
- fact_aggregated_bookings : contains propert_id, check_in date, room_category, successful_bookings and capacity
- fact_bookings : contains booking_id, property_id, booking_date, check_in date, check_out_date, number_of_guests, room_category, booking platform, ratings_given, booking_status, revenue_generated and revenue_realised

So Broadly, The sample dataset contains data of 25 hotels in 4 Cities - Mumbai, Dehi, Hyderabad aand Bangalore. They contain 4 types of rooms - Standard, Elite, Premium and Presidential. Bookings can be made offline or online via various alternatives. On cancellation, 40% of the amount is deducted and the rest is refunded.

##  :bar_chart: Dashboard

Built a 1-pager Dashboard using Tableau.

Tableau: [Link](https://public.tableau.com/app/profile/priya.palak7639/viz/HospitalityChallenge/DashboardInsights)

![Hospitality Challenge Dashboard](https://user-images.githubusercontent.com/96012488/193404766-a61b4c2d-13db-44dd-8c58-bf69c1cf3f8d.png)


## :bulb: Insights & Findings

 - The drop in Revenue during June (4.811 %) is accompanied by a drop in Occupancy % (1.54%). The Cancellation Rate has slightly reduced over the months and the Avg Rating has gone slightly up and down. However, there is no significant change in the Cancellation Rate and the Avg Rating over the months. 

 So, we may attribute the drop in Revenue to the drop in Occupancy %.
  
 ![Insight 1](https://user-images.githubusercontent.com/96012488/193406845-c21e38ff-d36a-4e27-ae02-aa8c99294588.png)
 
 
 - The Occupancy % is up during the start of the month and is down than usual during the mid and end weeks of the month.
 
 ![Insight 2](https://user-images.githubusercontent.com/96012488/193407365-0e1d18e9-23fc-4775-a6c0-d71d57821d72.png)
 
 
 - The Occupancy % is a lot higher on Weekends than on Weekdays.
 
 ![Insight 3](https://user-images.githubusercontent.com/96012488/193407491-e19aa2ec-fd89-439e-8be4-28cdd7fcf8a4.png)
 
 
 - On the left, we can see that over the months Mumbai has the highest contribution in Revenue, followed by Hyderabad, Bangalore and Delhi. While Delhi accounts for the lowest contribution in terms of Revenue, the City has consistently maintained the highest Occupancy % (which is even higher than the average) over the months.

On the right, we can see that Mumbai has the highest Capacity whereas Delhi has the lowest Capacity. And, this explains the lowest contribution of Delhi in Revenue despite maintaining the highest Occupancy %.

The company should consider looking into the factors responsible for the higher than average Occupancy % in Delhi and try to replicate them in other cities as well to regain the losing market share and increase its Revenue.

 Left| Right
:-----------:|:------------:
![Insight 4 1](https://user-images.githubusercontent.com/96012488/193407747-932c7769-20ce-4b2a-becf-dd0222131fff.png)| ![Insight 4 2](https://user-images.githubusercontent.com/96012488/193407773-0793df2e-bf05-4b06-877b-06549c929041.png)


- There are 4 hotels which have a very low Rating (around 2).

1. Atliq Bay Mumbai
2. Atliq Exotica Hyderabad
3. Atliq Grands Bangalore
4. Atliq Seasons Mumbai

Also, these 4 hotels have Occupancy % quite lower than the average.
So, the company should pay special attention to these 4 hotels. It may consider finding out how the branches of the first 3 hotels in other cities are doing better and then take corrective measures accordingly.     

![Insight 5](https://user-images.githubusercontent.com/96012488/193408066-12ef6fb4-7e0b-4287-9d2c-9070d3eb8eab.png)


- The average Cancellation Rate for this company is 24.83% which is slightly higher than the industry average of 24% (shown on the left).

On the right, we can see the Cancellation Rate is slghtly higher on Weekdays than on Weekends. 
Also, we saw above that Occupancy % is already lower on Weekdays.

So, the company can have different policies for Cancellation by Day Type to reduce the cancellations and increase Revenue realised on Weekdays.

Left|Right
:---:|:---:
![Insight 6 1](https://user-images.githubusercontent.com/96012488/193408637-0b427f3c-751e-43bc-b37f-0a59888b925c.png)|![Insight 6 2](https://user-images.githubusercontent.com/96012488/193408654-a75810d1-e38a-4a44-9a24-ded3e9a584bd.png)


- Only 5% of the bookings are happenning offline. More than 40% of bookings is happenning via 'Others' platform, followed by MakeYourTrip which accounts for almost 20% of the bookings.

The company should look into this 'Others' Platform and inspect what it consists of to plan its marketing srategies better. This can help the company regain its lost market share.


![Insight 7](https://user-images.githubusercontent.com/96012488/193408984-09ae3196-03c4-4ca5-986c-57c74a452479.png)







