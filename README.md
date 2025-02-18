
# 🏨 Predicting Hotel Cancellations
## 📌 Project Overview
A hotel is looking to increase revenue by reducing the number of booking cancellations. The goal of this project is to analyze booking data and predict which reservations are likely to be canceled, allowing the hotel to take proactive steps such as offering discounts or overbooking management.

This project applies data exploration, visualization, and machine learning techniques to uncover patterns and build a predictive model.

## 📂 Dataset Details
The dataset consists of hotel booking records, including information on guests, booking details, previous cancellations, special requests, and pricing.

## 📊 Data Dictionary

| Column                                  | Description                                              |
|-----------------------------------------|----------------------------------------------------------|
| `Booking_ID`                            | Unique identifier of the booking.                       |
| `no_of_adults`                          | The number of adults.                                   |
| `no_of_children`                        | The number of children.                                 |
| `no_of_weekend_nights`                  | Number of weekend nights (Saturday or Sunday).         |
| `no_of_week_nights`                     | Number of week nights (Monday to Friday).              |
| `type_of_meal_plan`                     | Type of meal plan included in the booking.             |
| `required_car_parking_space`            | Whether a car parking space is required.               |
| `room_type_reserved`                    | The type of room reserved.                             |
| `lead_time`                             | Number of days before the arrival date the booking was made. |
| `arrival_year`                          | Year of arrival.                                       |
| `arrival_month`                         | Month of arrival.                                      |
| `arrival_date`                          | Date of the month for arrival.                        |
| `market_segment_type`                    | How the booking was made.                              |
| `repeated_guest`                        | Whether the guest has previously stayed at the hotel.  |
| `no_of_previous_cancellations`          | Number of previous cancellations.                      |
| `no_of_previous_bookings_not_canceled`  | Number of previous bookings that were not canceled.    |
| `avg_price_per_room`                    | Average price per day of the booking.                  |
| `no_of_special_requests`                | Count of special requests made as part of the booking. |
| `booking_status`                        | Whether the booking was cancelled or not.              |




## 🛠️ Project Workflow
### 1️⃣ Exploratory Data Analysis (EDA)

- Summary statistics of bookings.
- Correlations between different features.
- Trends in cancellations across different groups.
### 2️⃣ Data Visualization

- Cancellation rate by lead time.
- Impact of previous cancellations on new bookings.
- Effect of price, special requests, and parking on cancellations.
### 3️⃣ Machine Learning Model

- Train classification models (Random Forest, Decision Tree, Logistic Regression).
- Evaluate performance using accuracy, precision, recall, and F1-score.
