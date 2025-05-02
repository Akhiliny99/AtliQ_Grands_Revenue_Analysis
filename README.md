# 🏨 AtliQ Grands – Revenue Management Dashboard (Power BI Project)

## 📌 Project Overview

**AtliQ Grands** is a five-star hotel chain with properties across India. Due to rising competition and ineffective decision-making, the company has been experiencing a decline in revenue and market share in the luxury/business hotels segment.

As part of a strategic initiative, the company planned to implement **Business and Data Intelligence** for better decision-making. This Power BI dashboard project was developed to support the **Revenue Management** team in analyzing historical data and generating key performance insights.

## 🎯 Objective

- Analyze historical booking and revenue data across locations.
- Build and visualize industry-standard hospitality KPIs.
- Enable the Revenue Management team to track performance and take action.
- Highlight trends, patterns, and operational inefficiencies.

## 🛠 Tools & Technologies Used

- Power BI (Data modeling, DAX measures, visualizations)
- DAX (for calculated columns and performance metrics)
- Excel (source data cleaning and preparation)
- Star Schema Design for optimized modeling

## 📈 Key Metrics Developed

### 📅 Calculated Columns
`wm` Week number extracted from the date 
`Day Type` Categorizes days as 'Weekday' or 'Weekend' 

### 📊 DAX Measures
Total Bookings: The total number of bookings made.

Successful Bookings: The number of bookings that have a successful status.

Cancellation Rate: The percentage of bookings that were canceled.

No Show %: The percentage of bookings where customers did not show up.

Average Rating: The average feedback score provided by customers.

Revenue: The total revenue that has been realized.

ADR (Average Daily Rate): The average revenue per room sold, calculated by dividing total revenue by the number of rooms sold.

RevPAR (Revenue per Available Room): The revenue generated per available room, calculated by dividing total revenue by the total capacity.

Occupancy Rate: The percentage of rooms that were checked out compared to the total room capacity.

DUIN / DRRN / DRAN: Daily room utilization metrics that track room occupancy and availability.

Bookings by Room Class / Platform: A breakdown of revenue sources based on room class or booking platform.

WoW Change %: The week-over-week percentage change for key metrics like revenue, ADR, RevPAR, occupancy, and realization.


