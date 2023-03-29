# Hotel_Booking-EDA-Project

The success factoring a profitable hotel industry has been changing over time, driven by global competition and increasingly high customer expectations. Hotels focus on customer satisfaction and to exceed customer expectations. We have a hotel booking dataset containing information for city and resort hotels. This dataset has 32 variables with around 1,19,000 entries. It is collected in order to predict hotel bookings and its probability of cancellation. Some attributes here are to understand what factors do bring in the revenue for the business. Some attributes show the customers preference for booking whereas some attributes show the factors leading to cancellations. We have a hotel booking dataset. We are using our Python skills to perform EDA and gain informative insights about factors in hotel bookings and how they affect hotel booking

In our data study we have 2 types of hotels- the resort type and city hotel type. There are factors in the study which affect the business of the hotels. Factors such as location, ADR, Deposits charged, wait time, etc. We also have channels like distribution channel, Market segment to focus on to get more revenue.

# Project Goal
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. Purpose of our study is to find the best time to book a hotel room. The optimal length of stay in order to get the best daily rate. Study on special requests.We explore and analyze the data to discover important factors that govern the bookings.

# Built With
Python
Pandas
NumPy
Plotly

# Exploratory Data Analysis:-
In this study we have sample data about the hotel industry that is not processed for use. Unprocessed data gives inaccurate results. To process this data is called data cleaning. We have cleaned the data by handling null values, outliers and dropping unwanted columns.

# Data Cleaning
# Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.

Country: - This has null values less than 5% thus the null values are filled with the mode value.

Children and babies: - There are only 4 null values so the null value is filled with mean

# Handling Outliers
An outlier is an extremely high or extremely low data point relative to the nearest data point and the rest of the neighboring co-existing values in a data graph or dataset we work with. We have used the Interquartile range method to handle outliers. To find the interquartile range (IQR), ​we first find the median (middle value) of the lower and upper half of the data. These values are quartile 1 (Q1) and quartile 3 (Q3). The IQR is the difference between Q3 and Q1.

# Data study
i) UNIVARIATE ANALYSIS: Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

ii) BIVARIATE ANALYSIS: Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

iii) MULTIVARIATE ANALYSIS Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.

# List of original variables:
* hotel - Hotel (H1 = Resort Hotel or H2 = City Hotel)
* is_canceled - Value indicating if the booking was canceled (1) or not (0)
* lead_time - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
* arrival_date_year - Year of arrival date
* arrival_date_month - Month of arrival date
* arrival_date_week_number - Week number of year for arrival date
* arrival_date_day_of_month - Day of arrival date
* stays_in_weekend_nights - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
* stays_in_week_nights - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
* adults - Number of adults
* children - Number of children
* babies - Number of babies
* meal - Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board       (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)
* country - Country of origin. Categories are represented in the ISO 3155–3:2013 format
* market_segment - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* distribution_channel - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* is_repeated_guest - Value indicating if the booking name was from a repeated guest (1) or not (0)
* previous_cancellations - Number of previous bookings that were cancelled by the customer prior to the current booking
* previous_bookings_not_canceled - Number of previous bookings not cancelled by the customer prior to the current booking
* reserved_room_type - Code of room type reserved. Code is presented instead of designation for anonymity reasons.
* assigned_room_type - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation     reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.
* booking_changes - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
* deposit_type - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made;   * Non   Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
* agent - ID of the travel agency that made the booking
* company - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
* days_in_waiting_list - Number of days the booking was in the waiting list before it was confirmed to the customer
* customer_type - Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group –     when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking;           Transient-party – when the booking is transient, but is associated to at least other transient booking
* adr - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
* required_car_parking_spaces - Number of car parking spaces required by the customer
* total_of_special_requests - Number of special requests made by the customer (e.g. twin bed or high floor)
* reservation_status - Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in   but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why
* reservation_status_date - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the         booking canceled or when did the customer checked-out of the hotel

# Data Visualization :-
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. The graphs used here for study are: -

Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.

Geo Mapping.

# Conclusion :-
Majority of people prefer A-room type so hotels should increase their numbers to get more revenue.

Chances of cancellation is high when there are no deposits taken by hotels, so hotels should take minimum deposits to minimise the rate of cancellation.

Transient customers cancels more often but when people book in groups it leads to lesser cancellations, hence hotels should provide some offers focusing transient customers to decrease cancellations.

Maximum number of bookings are in the month May to August, so hotels should provide exciting deal to customers to increase their booking in off season. As hotels are getting less repeated customers so management should take customer’s feedback and improve the hotel facilities to increase the count of their repeated guests.

Every year there is 25-30% cancellation for resort hotels and 40-45% cancellation for city hotels.
