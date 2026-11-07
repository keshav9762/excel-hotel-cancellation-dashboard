# 🏨 Hotel Booking Cancellation Dashboard

### An Excel-based data analysis project exploring hotel booking trends, guest demographics, and cancellation patterns.

---

## 📊 Dashboard Preview
*(Note: Upload your dashboard screenshot to the repository and name it `Dashboard.png`)*
![Dashboard Preview](Dashboard.png)

## 🎯 Project Overview
This project is an interactive Excel dashboard designed to analyze historical booking data and uncover insights regarding booking cancellations. It provides business intelligence for the hospitality industry by tracking how guest types, room assignments, and seasonality impact the likelihood of a guest canceling their stay.

## 🛠️ Tools & Techniques Used
- **Microsoft Excel**: Data cleaning, manipulation, and visualization.
- **Pivot Tables & Pivot Charts**: Aggregated large datasets to summarize total metrics and trends.
- **Data Processing**: Utilized Excel formulas to clean data and derive new metrics (e.g., `room_status` and `guest_type`).
- **Interactive Dashboard**: Built a dynamic dashboard using Slicers for interactive data exploration.

## 🗂️ Dataset Structure
The project workbook contains three main sheets:

1. **`hotel_bookings` (Raw Data)**: Contains the historical booking records. Key columns include:
   * **Booking Info**: `hotel`, `is_canceled`, `reservation_status`, `reservation_status_date`
   * **Date Details**: `arrival_date_year`, `arrival_date_month`
   * **Demographics**: `adults`, `children`, `babies`, `country`
   * **Room Details**: `reserved_room_type`, `assigned_room_type`
   * **Custom Calculated Columns**: 
     * `room_status` (Categorizes if the guest received their "Desired" room or not)
     * `guest_type` (Categorizes guests into groups like "Couples", "Family", etc.)
2. **`Pivot`**: Contains the pivot tables used to aggregate the data for the visualizations.
3. **`Dashboard`**: The interactive visual interface.

## 📈 Key Insights & Features

1. **Overall Performance**: Tracks the total volume of bookings versus total cancellations.
2. **Hotel Type Comparison**: Analyzes the booking and cancellation split between "City Hotel" and "Resort Hotel", showing that City Hotels experience a significantly higher volume of both bookings and cancellations.
3. **Room Preference Impact**: Evaluates how receiving a "Desired" vs. "Un-Desired" room impacts the likelihood of a guest canceling their stay.
4. **Guest Demographics**: Breaks down booking and cancellation statistics by guest types (Couples, Family, Singles, etc.).
5. **Monthly Trends**: A month-over-month bar chart tracking booking volume versus cancellations across the year to identify seasonal trends.

## 🚀 How to Use
1. Clone this repository or download the `Book1.xlsx` file directly.
2. Open the file in Microsoft Excel.
3. Navigate to the **`Dashboard`** sheet.
4. Use the Slicers (if applicable) to dynamically filter the charts by specific years, hotel types, or months.
