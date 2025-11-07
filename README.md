# Hotels-bookings-analysis
Data Exploration & Insights

# Project Overview

This project focuses on analyzing hotel booking data to uncover patterns related to cancellations, booking preferences, customer behavior, and factors affecting occupancy.
The goal is to convert raw data into meaningful insights which help businesses make informed decisions.

# Objectives

Understand booking patterns and cancellation trends

Identify which factors influence cancellations

Explore customer preferences (hotel type, stay duration, room type, lead time)

Visualize insights using data analytics and Python

# Steps Performed

Imported and cleaned the dataset

Handled missing values

Performed exploratory data analysis (EDA)

Visualized insights using graphs

Interpreted results and business conclusions

# Dataset Description

This project uses a large dataset containing hotel booking records.
Each row represents one booking, and the dataset includes the following columns:

**Column Name	Description**

**booking_id:**            	Unique ID assigned to every booking<br>
**booking_date:**	          Date when the booking was made<br>
**check_in_date_x:**        Customer's scheduled check-in date<br>
**checkout_date:**         	Customer's scheduled checkout date<br>
**no_guests:**            	Total number of guests included in the booking<br>
**room_category:**          Type of room booked (Standard, Deluxe, Suite, etc.)<br>
**booking_platform:**       Channel used for booking<br>
**ratings_given:**         	Rating given by the customer (if booking was completed)<br>
**booking_status:**       	Whether the booking was Successful, Cancelled, or No-show<br>
**revenue_generated:**    	Total expected revenue from the booking<br>
**revenue_realized:**     	Actual revenue received after cancellations/refunds<br>
**successful_bookings:**  	Count of successful bookings<br>
**capacity:**              	Maximum room occupancy allowed<br>
**occupancy_rate:**       	Percentage of room occupancy during stay<br>
**money_paid_back:**      	Refund amount given back in case of cancellation<br>
**days_spent:**	            Actual number of days customer stayed<br>

# Key Insights from the Analysis

City hotels receive more bookings than resort hotels.

Higher cancellation rates occur where the lead time (time between booking and arrival) is large.

Bookings through online Travel Agencies (OTA) have the highest cancellation rate.

Longer stay duration and repeated guests tend to have lower cancellation probability.

These insights help hotels improve booking strategies, pricing, and customer retention.

# Conclusion

This analysis provides useful insights for hotel businesses to:

Improve revenue management

Reduce cancellation rates

Understand customer booking patterns

It demonstrates data analysis skills using Python and visualization tools, making it a strong portfolio project.
