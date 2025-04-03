# Airline Performance Analysis using Power BI

## Problem Statement
The airline industry is highly dynamic, with numerous daily operations, including flight scheduling, passenger management, and ticket booking. Analyzing and managing this data effectively is crucial for operational efficiency, customer satisfaction, and strategic decision-making. This project aims to streamline and analyze airline operations using Power BI to uncover insights and improve management processes.

## Datasets Used
1. **Flight Information**: Contains details about flights, including FlightID, FlightNumber, Airline, Destination, and Status.
2. **Passenger Information**: Includes PassengerID, FlightID, and SeatNumber.
3. **Ticket Information**: Covers ticket bookings, including TicketID, FlightID, and BookingStatus.

## Objectives
The primary objective of this project is to analyze and visualize airline data to gain insights into **flight operations, passenger management, and ticketing**. The project will use **Power BI** features to transform, model, and visualize data, creating a comprehensive dashboard for decision-making.

## Tasks Breakdown
### **Task 1: Data Extraction and Transformation in Power Query**
- Extract and clean data from CSV files.
- Handle missing values, duplicates, and format columns.

### **Task 2: Conditional and Custom Columns**
- Classify flights as **“best”** or **“to be improved”** based on status.

### **Task 3: Column from Examples and Replace Values**
- Extract flight numbers using **Power Query's Column from Examples**.
- Standardize values in the **Status** column.

### **Task 4: Merge Queries and Merge Columns**
- Merge **Flight Information** and **Passenger Information** based on FlightID.
- Merge **SeatNumber** and **PassengerID** to create a unique identifier for each passenger.

### **Task 5: Create Relationships**
- Establish relationships between datasets (e.g., FlightID linking flights and tickets).

### **Task 6: DAX Calculations**
- Find the **total number of passengers** for a specific flight.
- Calculate the **total tickets booked**.
- Create a **filtered table for best flights**.

### **Task 7: Visualizations**
- Multi-card chart for **passenger count per airline**.
- **Bar chart** to compare passengers per airline.
- **Donut chart** for ticket booking distribution.

### **Task 8: Advanced Visualizations**
- **Decomposition tree** to break down flights by airline and destination.
- **Q&A visual** for booking statuses by total tickets.

### **Task 9: Interactive Features**
- **Slicers** for filtering by destination and airline.
- **Bookmarks** for saving different views.
- **Drill-through feature** to explore airline-specific details.

### **Task 10: Final Report and Dashboard**
- Create a **Power BI workspace** named *Airline*.
- Design a comprehensive **dashboard** with key insights.
- Implement **Row-Level Security (RLS)** for restricted airline-specific access.
- Set up **scheduled data refresh at 5 PM daily**.

## Technologies Used
- **Power BI** (Data Transformation, Visualization, and Dashboarding)
- **DAX** (Custom calculations and metrics)
- **Power Query** (Data Cleaning and Preprocessing)

## How to Use This Project
1. Load the dataset into **Power BI**.
2. Navigate through the dashboard for **key insights on airline performance**.
3. Use slicers and drill-through features to explore specific areas of interest.

## Project Files
- `Airline_Performance.pbix` - Power BI report file with all analyses and dashboards.
- `Data_Files/` - Contains raw CSV datasets used for analysis.

## Contributors
- **Vinay Uppada**

## Acknowledgments
- Data used for **Airline Operations Analysis**.

---

Feel free to explore and provide any feedback! 🚀
