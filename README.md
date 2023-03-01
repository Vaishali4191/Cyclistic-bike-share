# Cyclistic-bike-share
Capstone project for Google Data Analytics Certificate

-- Introduction

Data is from Cyclistic, a bike-share company in Chicago, which is a fictional company and is made available by Motivate International Inc under Data License Agreement. The bikes can be unlocked from one station and returned to any other station in the system at any time. Customers are divided in Casual and Annual members. Goal is to design marketing strategies aimed at converting casual riders into annual members.

-- Objective

Provide the marketing team with insights regarding customer behavior to help them design marketing strategies aimed at converting casual riders into annual members.
Q : How do annual members and casual riders use Cyclistic bikes differently?

-- Prepare and Process

Created separate columns for Date and Time and changed the data type of start_station_id and end_station_id in Excel.
After that uploaded all 12 files into Big Query and combined them into one.
I have not deleted NULL here as it might impact the analysis.

![Dashboard](https://user-images.githubusercontent.com/126613112/222256405-f08727ee-962c-4276-b44b-a688ece2e54f.png)

-- Summary

Annual members' rides are higher than the casual members.
The number of trips is highest during summer months and lowest during winter months for both one-way and round trips. 
The Usage of Docked bikes is higher than the classic and electric bikes. It can be because of availability or because people just don’t want to use the electric bike because of range anxiety.
Annual members are using bikes consistently throughout the week. It can be because annual members are using bikes for work as well as weekend trips.
Casual members' bike usage is lower on weekdays and almost equal on weekends. This can be because casual members prefers to use bikes for weekend trips and not for daily work commutes.
The Demand for bikes is higher at 5 pm, so people must be using bikes for commuting back to home after work but 9 am usage is not as high as 5 pm.

-- Recommendations

Check why Docked bike’s usage is higher than the other 2 bikes. It can be because of availability or range anxiety.
Introduce annual membership for only weekends.
Promote a healthy and greener lifestyle.
Advertise annual membership and its benefits on popular sites or nearby stations.
Introduce seasonal discounts or referral rewards.
