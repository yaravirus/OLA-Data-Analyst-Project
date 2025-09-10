# OLA-Data-Analyst-Project
## Project Objective

The goal of this project was to analyze cab booking patterns for OLA in Bengaluru city. Using SQL and Power BI, I created an interactive dashboard to track booking performance, cancellations, revenue, and customer/driver ratings. The objective was to identify key trends, cancellation reasons, and opportunities to improve customer experience.

# Dataset Used

Synthetic dataset with 100,000+ records for July 2024.

Key Columns:

Booking_ID, Date, Time

Booking_Status (Success, Canceled by Driver, Canceled by Customer, Driver Not Found)

Vehicle_Type (Auto, Prime Plus, Prime Sedan, Mini, Bike, E-Bike, Prime SUV)

Pickup & Drop Location (50 dummy areas in Bengaluru)

Booking_Value, Ride_Distance

Cancelation reasons (Customer & Driver specific)

Ratings (Driver & Customer)

Payment Method

Constraints applied:

62% rides successful

< 7% cancelled by customers

< 18% cancelled by drivers

< 6% incomplete rides


# Questions / KPIs

📈 Total Bookings & Booking Value

🚖 Ride Volume Over Time

🛺 Booking Status Breakdown (Success vs. Cancellations)

🚗 Top Vehicle Types by Ride Distance & Revenue

💸 Revenue by Payment Method

❌ Cancelled Rides Analysis (by Customer & Driver reasons)

⭐ Customer vs. Driver Ratings distribution

👥 Top 5 Customers by Total Booking Value

# Process Followed

## Data Preparation

Created dataset using Python & Excel (synthetic records).

Cleaned data for null values, outliers, and formatting.

Loaded dataset into SQL & Power BI.

SQL Analysis

Queries to calculate ride counts, cancellations, top customers, and average ratings.

Example: finding cancellation counts by driver reasons, average ride distance per vehicle type.

Power BI Dashboard

Built multiple report pages:

Overall: Ride volume trends & booking status.

Vehicle Type: Revenue and distance analysis.

Revenue: Payment methods & customer contribution.

Cancellation: Customer vs. driver cancellation reasons.

Ratings: Driver and customer ratings distribution.
