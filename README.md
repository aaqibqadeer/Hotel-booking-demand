# Hotel Booking Demand

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
All personally identifying information has been removed from the data.

We will perform exploratory data analysis with python to get insight from the data.  

This article on medium explains the entire the process  
[Exploratory Data Analysis of the Hotel Booking Demand with Python](https://medium.com/@aaqibqs/exploratory-data-analysis-of-the-hotel-booking-demand-with-python-200925230106)


## Table of Content
- [Motivation](#Motivation)
- [Tools and Libraries Used](#Tools-and-Libraries-Used)
- [Files](#Files)
- [Result](#Result)
- [Dataset Information](#Dataset-Information)
  - [Acknowledgements](#Acknowledgements)

## Motivation

### We have tried to answer the following Questions
1. How Many Booking Were Cancelled?
2. What is the booking ratio between Resort Hotel and City Hotel?
3. What is the percentage of booking for each year?
4. Which is the most busy month for hotel?
5. From which country most guest come?
6. How Long People Stay in the hotel?
7. Which was the most booked accommodation type (Single, Couple, Family)?

### After that we made the predictive model to predict whether the booking will be cancelled or not

**We will:**
- Perform the Feature Engineering to make new featuers
- Perform the Data Selection to select only relevant features
- Tranform the Data (Categorial to Numerical)
- Split the data (Train Test Split)
- Model the data (Fit the Data)
- And finally Evaluate our model

## Tools and Libraries Used
We have used Python 3 to its following packages:
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- pycountry

## Files
This repository contains two files other than readme file

**Hotel Booking.ipynb:** Jupyter Notebook file contains all the python code, documentation and visualization  
**hotel_bookings.csv:** Our dataset file

**Dataset contains following features:**
1. hotel
2. is_canceled
3. lead_time
4. arrival_date_year
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_week_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellations
19. previous_bookings_not_canceled
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent
25. company
26. days_in_waiting_list
27. customer_type
28. adr
29. required_car_parking_spaces
30. total_of_special_requests
31. reservation_status
32. reservation_status_date


## Result

We learned that
1. Almost 35% of bookings were canceled.
2. More than 60% of the population booked the City hotel.
3. More than double bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year.
4. Most bookings were made from July to August. And the least bookings were made at the start and end of the year.
5. Portugal, the UK, and France, Spain and Germany are the top countries from most guests come, more than 80% come from these 5 countries.
6. Most people stay for one, two, or three.
-> For Resort hotel, the most popular stay duration is three, two, one, and four days respectively.
-> For City hotel, most popular stay duration is one, two, seven(week), and three respectively
7. Couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly

<p float="left" align="middle">  
  <img src="https://user-images.githubusercontent.com/37020354/79042910-0c418780-7c15-11ea-8ddb-f17cf6b1fb2c.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042912-0e0b4b00-7c15-11ea-956c-c4ffd1c8525f.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042909-0b105a80-7c15-11ea-8d4b-317802f73077.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042911-0cda1e00-7c15-11ea-98ea-dcc11e217f32.png" />
</p>

<!---
-- ![4](https://user-images.githubusercontent.com/37020354/79042911-0cda1e00-7c15-11ea-98ea-dcc11e217f32.png)
![1](https://user-images.githubusercontent.com/37020354/79042912-0e0b4b00-7c15-11ea-956c-c4ffd1c8525f.png)
--->





## Dataset Information:  
Data was posted on Kaggle by Jesse Mostipak.
It is available to download Here:
https://www.kaggle.com/jessemostipak/hotel-booking-demand


#### Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.
