# 🏨 Atliq Hotel Booking & Revenue Analysis

## 📌 Objective
To analyze booking, revenue, occupancy, and performance trends across Atliq’s hotel properties in various cities using datasets like:

- `fact_bookings`
- `fact_aggregated_bookings`
- `dim_rooms`
- `dim_hotels`
- `dim_date`

The aim is to generate **actionable insights** for improving operational efficiency and driving better business outcomes in the hospitality domain.

---

## 🔍 Key Insights

### 🛏️ Room Category Occupancy Rates
- **Presidential rooms** had the highest average occupancy (≈ 59.3%).
- All room types (Standard, Premium, Elite, Presidential) hovered around **58–59%** occupancy.

### 🏙️ City-wise Occupancy
- **Delhi** had the highest average occupancy rate (≈ 61.6%), followed by:
  - Hyderabad
  - Mumbai
  - Bangalore

### 📅 Weekday vs. Weekend Trends
- **Weekend occupancy**: 72.39%  
- **Weekday occupancy**: 50.90%  
→ Indicates stronger **leisure demand** over weekends.

### 📈 June Monthly Occupancy by City
- **Delhi**: 62.47%  
- **Hyderabad**: 58.46%  
- **Mumbai**: 58.38%  
- **Bangalore**: 56.58%

### 💰 Revenue Realized per City
- **Mumbai** led with ₹668M+
- Followed by: Bangalore, Hyderabad, and Delhi

### 🌐 Booking Platform Usage
- Top platforms: `Others`, `Makeyourtrip`, `Logtrip`
- **Direct bookings** (online/offline) had a **smaller share**

### ⚠️ Overbooked Instances
- Properties like ID `17558` had 30 bookings vs. a 19-room capacity  
→ Signals **operational inefficiencies**

### 🧹 Data Cleaning Issues Identified
- Negative guest counts
- Revenue outliers (e.g., bookings over ₹2.94L)
- All cleaned for accurate analysis

---

## 📊 Visualizations Used

- **Bar Charts**  
  → Booking platform distribution, average occupancy per city (June)

- **Descriptive Statistics**  
  → Summary metrics for numerical features

- **Time-Based Analysis**  
  → Weekday vs. weekend occupancy patterns

- **Occupancy Calculation**  
  → `OCC_Pct` calculated to determine room utilization

- **Data Merges**  
  → Combined datasets using `property_id` and `check_in_date` for consolidated insights

---

## ✅ Recommendations

### 📅 Improve Weekday Occupancy
- Run **mid-week promotions**
- Offer **business traveler discounts**

### 🚫 Capacity Management
- Investigate properties consistently **overbooked**
- Implement better **capacity monitoring**

### 💳 Optimize Platform Usage
- Promote **direct bookings** with:
  - Loyalty rewards
  - Exclusive discounts

### 📍 City-Based Strategy
- Invest more in **Delhi** and **Mumbai**
- Explore reasons behind **Bangalore’s** lower performance

### 🛎️ Refine Room Category Strategy
- Presidential rooms show promise — consider:
  - **Bundling offers**
  - **Upselling campaigns**

### 🧼 Data Hygiene
- Improve **data entry validation** to prevent:
  - Negative guest counts
  - Unrealistic revenue values

### 🗂️ Expand August Data Integration
- Ensure future monthly datasets are:
  - **Appended**
  - **Harmonized** for seamless analysis

---

## 📬 Contact
For queries or collaboration: [Email : Aashishchauhan261@gmail.com or Linkedln : https://www.linkedin.com/in/ashish-chauhan555/]
