 
 
 Ford GoBike Data Visualization

 By Ahmed Elhalw
  
  
   Introduction: 
  
  
   ford-goBike-dataset-exploration is a project doing exploratory visualization on the bike trip dataset. 
   This dataset includes information about individual rides in 2019
   The dataset can be downloaded from https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv.
   

The dataset includes:

 1.duration_sec: Trip Duration (seconds)
 2.start_time: Start Time and Date
 3.end_time: End Time and Date
 4.start_station_id: Start Station ID
 5.start_station_name: Start Station Name
 6.start_station_latitude: Start Station Latitude
 7.start_station_longitude: Start Station Longitude
 8.end_station_id: End Station ID
 9.end_station_name: End Station Name
 10.end_station_latitude: End Station Latitude
 11.end_station_longitude: End Station Longitude
 12.bike_id: Bike ID
 13.user_type: User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
 14.member_birth_year: Member Year of Birth
 15.member_gender: Member Gender
 16.bike_share_for_all_trip: Boolean to track members who are enrolled in the "Bike Share for All" program for low-income residents
There are 183412 rows and 16 columns


Summary of Findings:

The age distrubution is right skewed with members of age between 25 to 40 years representing major partition of the dataset.
We Notice most of the bike ride duration is below 30 min, however the duration have a long tail of outliers may be due to users keeping their bike rented during work or forget to log off after finishing rides.
Males represent 75% of the dataset.
More than 90% of users are Subscribers to the ford go bike service.
The Females have the biggest duration mean on their rides. At the other side, men taking the shortest rides.
The members aged between 25-40 years tend to do the longest rides durations.
Customers may be keeping there bikes rented during working hours or forget to log off as we observe long rides over 10 hours and up to 20 hours.
The average age for males and females are quite equal around 36 years.
Higher numbers of subscribers are men then women.
Subscribers percentage is higher than customers regardeless of the gender.

 Insights for Presentation:
 
 Trip Duration is very dependendable on the age of the member.
 We notice that members aged between 25-40 years tend to do the longest rides durations.
 The average age for males and females are quite equal around 36 years.
 Higher numbers of subscribers are men then women.
 We Notice that most users prefer not to share the bikes regardless of there gender.
 Males represent 75% of the dataset, the plot show the average age for males and females are quite equal around 33 years of age.
 Both (Market st, San Francisco caltrain station2) are the highest starting and destination stations

 
 Resources:


https://www.kaggle.com/skostis/data-analysis-fordbike-with-ride-duration-predict
https://www.geeksforgeeks.org/python-datetime-module-with-examples/#datetime
https://stackoverflow.com/questions/14661701/how-to-drop-a-list-of-rows-from-pandas-dataframe
https://www.kaggle.com/chirag02/ford-gobike-data-analysis
