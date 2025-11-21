# Skyview_Analytics
✈️ Airline Data Management & Analysis Using Power BI

A complete end-to-end BI project showcasing data cleaning, modeling, DAX calculations, and dashboard development.

📌 Project Overview

The airline industry generates massive data around flights, passengers, bookings, and operations.
This Power BI project analyzes airline datasets to uncover operational insights, passenger trends, and ticket booking patterns to support better decision-making.

This project demonstrates the full BI workflow:
✔ Data cleaning
✔ Data modeling
✔ Power Query transformations
✔ DAX measures
✔ Interactive dashboards
✔ Row-Level Security (RLS)
✔ Scheduled refresh setup

🎯 Objective

To analyze and visualize airline operational data using Power BI, enabling insights into:
Flight performance
Passenger distribution
Ticket booking status
Airline and destination trends
Flight quality classification

🛠️ Tools & Technologies

Power BI Desktop
Power Query
DAX (Data Analysis Expressions)
Power BI Service
Data Modeling
Row-Level Security (RLS)

🗂️ Dataset Details

This project uses three datasets linked through FlightID:

Flight Information
Passenger Information
Ticket Information

🔧 Data Preparation & Cleaning

Performed in Power Query:
Removed duplicates in all three tables
Eliminated null values in SeatNumber
Fixed inconsistent formatting
Transformed columns for analysis
Ensured high-quality, clean data for accurate reporting.

🔗 Data Modeling

A structured star schema was created:
Flight_Information (One)
Passenger_Information (Many)
Ticket_Information (Many)
Configured relationships using FlightID as the primary key.
This allows seamless filtering across flights, passengers, and ticket records.

🧠 Enhanced Calculated Insights
✔ Conditional Flight Classification
Created a column to group flights into:
Best (On Time, Completed)
To Be Improved (Delayed, Cancelled)

✔ Extracted Flight Number
Used Column From Examples to extract numeric part from FlightNumber (AI-203 → 203).

✔ DAX Measures
Total passengers per flight
Total tickets booked
Best flights table using FILTER
Booking status calculations

📊 Dashboard & Visualizations

Key insights include:
Passenger Count by Airline
Airline D had the highest passenger volume.
Ticket Booking Status
44.44% Cancelled
30.56% Confirmed
Flights by Destination
Houston and Los Angeles were top destinations.

Interactive features include:
✔ Slicers for Airline & Destination
✔ Quick toggle views for airline-specific dashboards
✔ Multi-page navigation

🔐 Row-Level Security (RLS)

Configured RLS so that Airline A users can only see Airline A’s data.
Perfect for real-world enterprise use cases.

🔄 Scheduled Refresh

Set up an automatic refresh at 5 PM in Power BI Service to keep dashboards updated with the latest data.

⭐ Project Highlights

✔ Real-world airline analytics use case
✔ Clean data model with proper relationships
✔ DAX-based KPIs
✔ RLS implementation
✔ Automatic refresh configuration
✔ Fully interactive dashboard
