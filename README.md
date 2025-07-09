# Airline Performance Analysis using Power BI

## Overview
This project analyzes airline operations using Power BI to uncover insights in flight schedules, passenger counts, and ticket statuses. The dashboard was built using Power Query, data modeling, DAX, and interactive visuals, aimed at improving operational efficiency and customer satisfaction.

---

## Datasets Used
1. `Flight_Information.xlsx` – FlightID, FlightNumber, Airline, Destination, Status  
2. `Passenger_Information.xlsx` – PassengerID, FlightID, SeatNumber  
3. `Ticket_Information.xlsx` – TicketID, FlightID, BookingStatus

---

## Tools & Techniques
- **Power BI Desktop**
- **Power Query**
- **Data Modeling (one-to-many via FlightID)**
- **DAX Calculations**
- **Drillthrough Pages, Slicers, Bookmarks**
- **Power BI Service: Row-Level Security (RLS), Scheduled Refresh**

---

## Key Features

### Data Preparation & Modeling
- Cleaned all 3 datasets using Power Query (removed nulls, duplicates, corrected data types)
- Established relationships via `FlightID` to build unified data model

### DAX Measures & Columns
- Calculated total tickets booked and passenger count per flight
- Created `PerformanceStatus` column: `"Best"` for on-time flights, `"To Be Improved"` otherwise
- Extracted numeric flight numbers with Column From Examples

### Interactive Dashboard Visuals
- **Stacked Bar Chart**: Passenger Count by Airline  
- **Donut Chart**: Ticket Booking Status Distribution  
- **Stacked Column Chart**: Flights by Airline and Destination  
- **Slicers**: Filter by Airline and Destination  
- **Bookmarks**: Preset views for Airlines A–D  
- **Drillthrough Pages**: Airline-specific summaries of passenger and ticket data

---

## Power BI Service Integration
- Implemented **Row-Level Security** for "Airline A" users using DAX rules  
- Enabled **daily scheduled refresh** at 5:00 PM on Power BI Service

---

## Dashboard Preview
![image](https://github.com/user-attachments/assets/3c0ea655-b1f9-4633-9821-d091ded12107)


---

## Repository Files
| File | Description |
|------|-------------|
| `AirlineDashboard.pbix` | Power BI file with full model and visuals |
| `dashboard.png` | Final dashboard screenshot |
| `README.md` | Project documentation (this file)

---

## Conclusion
This project showcases the full data workflow — from raw Excel files to a robust, interactive dashboard — and demonstrates how Power BI can drive better decision-making in complex, real-time operational environments.

---

## 📫 Contact
📧 nikhilskumar02@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/nikhilskumar2703)  
💻 [GitHub](https://github.com/Nikhil-S-Kumar-02)
