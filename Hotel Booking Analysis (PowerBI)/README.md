# Hotel Booking Analysis PowerBI

Have you ever wondered when is the most suitable time to reserve a hotel room? Or what length of stay gives you the best daily rate? With this hotel booking data set, you can predict the likelihood of receiving unusual special requests. It comprises booking information for a city hotel and a resort hotel, such as when the booking was made, the duration of the stay, the number of adults, children, and/or infants, as well as the number of available parking spaces. Notably, the data does not include any personal information.

### Dataset Exploration
 We have a total of 119390 rows and 32 columns.
 
### Data Description:
**Hotel:** Hotel(Resort Hotel or City Hotel)

**is_canceled:** Value indicating if the booking was canceled (1) or not (0)

**lead_time:** Number of days that elapsed between the entering date of the booking into the PMS and the arrival date*

**arrival_date_year:** Year of arrival date

**arrival_date_month:** Month of arrival date

**arrival_date_week_number:** Week number of year for arrival date

**arrival_date_day_of_month:** Day of arrival date

**stays_in_weekend_nights:** Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

**stays_in_week_nights:** Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

**adults:** Number of adults

**children:** Number of children

**babies:** Number of babies

**meal:** Type of meal booked. Categories are presented in standard hospitality meal packages:

**country:** Country of origin.

**market_segment** Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**distribution_channel:** Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

**is_repeated_guest:** Value indicating if the booking name was from a repeated guest (1) or not (0)

**previous_cancellations:** Number of previous bookings that were cancelled by the customer prior to the current booking

**previous_bookings_not_canceled:** Number of previous bookings not cancelled by the customer prior to the current booking

**reserved_room_type:** Code of room type reserved. Code is presented instead of designation for anonymity reasons.

**assigned_room_type:** Code for the type of room assigned to the booking.

**booking_changes:** Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

**deposit_type:** Indication on if the customer made a deposit to guarantee the booking.

**agent:** ID of the travel agency that made the booking

**company:** ID of the company/entity that made the booking or responsible for paying the booking.

**days_in_waiting_list:** Number of days the booking was in the waiting list before it was confirmed to the customer

**customer_type:** Type of booking, assuming one of four categories

**adr:** Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

**required_car_parking_spaces:** Number of car parking spaces required by the customer

**total_of_special_requests:** Number of special requests made by the customer (e.g. twin bed or high floor)*

**reservation_status:** Reservation last status, assuming one of three categories

**Canceled:** booking was canceled by the customer

**Check-Out:** customer has checked in but already departed

**No-Show:** customer did not check-in and did inform the hotel of the reason why

**reservation_status_date:** Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel

## EDA (Exploratory Data Analysis)
**Univariate Analysis**

### 1) Which type of hotel is in the dataset?
- Two types : City Hotel and Resort Hotel.
       
### 2) In which month has the highest bookings/total guest by hotel happened?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi1.jpg)
    
   #### Observation
- July and August months had the most Bookings. Summer vaccation can be the reason for the bookings.
       
### 3) Which type of food is mostly preferred by the guests?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi2.jpg)
       
   #### Types of meal in hotels:
   - BB - (Bed and Breakfast)
   - HB - (Half Board)
   - FB - (Full Board)
   - SC/Undefined - (Self Catering)
   
   #### Observation
 - So the most preferred meal type by the guests is BB( Bed and Breakfast)** 
 - HB- (Half Board) and SC- (Self Catering) are equally preferred.**
 
 ### 4) What is the total number of required_car_parking_spaces?
 ![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi3.html)
 
 - Here is_required = 0 means guest don't required parking and is_requires = 1 means parking required.
        
   #### Observation
 - For city hotels and resort hotels majority of the guest did not reqired parking space but few required parking space.

#### 5) Which Hotels has the most repeated guests?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi1.jpg)

   #### Observation
- City Hotel has slightly more repeated guests than the Resort Hotels.

#### 6) Which year has the most booking cancelled or most booking cancelled ?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi1.jpg)

   #### Observation
- Year 2015 had the highest booking cancelled compare to guest who did not cancelled their bookings.
- There was signigicant dropped in the cancellation of the booking in the year 2016 while the more booking was done which was highest among year 2015 and 2017.
- In the year 2017 there was continously dropped in the booking cancellation however there slight declined in the booking which was not cancelled after the year 2016.

#### 7) Which Market Segment has the higest cancellation rate?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi6.jpg)
   #### Observation
  - 'Groups' and 'Online T/A' has the highest cancellation in both type of cities
  In order to reduce the booking cancellations hotels need to set the refundable/ no refundable and deposit policies policies
  
#### 8) Which Country has highest booking which was not cancelled?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi7.jpg)

   #### Observation
- Portugal has highest non-cancellation booking compare to other countries.

  
#### 9) Which Customer segment has highest booking?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/pwerbi10.jpg)
   #### Observation
    - Transient and Transient Party both have almost equal bookings in the hotel with 49.31% and 47.53% respectively.
  
#### 10) Which months of the years in the span of three years like 2015, 2016 and 2017 have the number of stays in week nights and weekend night ?
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/pwr11.jpg)
    
   #### Observation
     - From the graph we can say number of stays in week nights was more from the month june then it continiously increasing after two months but in the last month there was dropped in the number of stays in nights while weekend night stays was not more prefer by the customer there may be price difference because in weeks the actual price may be much lower compared to price in the weekend night.


#### Dashboard 1 
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi8.jpg)

#### Dashboard 2
![Hotel Booking](https://github.com/Pramit613/Data-Analyst-Portfolio-Pramit-Parikh/blob/main/Hotel%20Booking%20Analysis%20(PowerBI)/Screenshots%20of%20Charts/Powerbi9.jpg)

#### Conclusion

- City hotels are the most preferred hotel type by the guests. We can say City hotel is the busiest hotel.
- Most of the customers do not require car parking spaces.
- BB( Bed & Breakfast) is the most preferred type of meal by the guests.
- Maximum number of guests were from Portugal, i.e. more than 25000 guests.
- Optimal stay in both the type hotel is less than 7 days. Usually people stay for a week.
- Majority of the  bookings were made through TA/TO (travel agents/Tour operators).
- Most of the customers do not require car parking spaces.




   

       

