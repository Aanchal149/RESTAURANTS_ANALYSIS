📊 Restaurant Data Analysis 

## 📁 Project Overview

This project analyzes restaurant data across 141 cities (\~10,000+ entries) to uncover insights into customer satisfaction, service performance, pricing dynamics, and city-wise opportunities for expansion. The dataset includes restaurant-level attributes like ratings, votes, price range, cuisines, service availability, and location.

---

## 🛠️ Tools Used

* **Microsoft Excel** – Data cleaning, unpivoting, rating segmentation
* **Power BI** – Interactive dashboarding, advanced DAX, visual storytelling
* **DAX (Power BI)** – For KPI calculations, adjusted metrics, and ranking logic

---

## 📌 Excel Analysis – Initial Steps

Excel was used as a **foundational platform** for early data exploration:

### ✅ Tasks Performed in Excel:

1. **Removed Duplicates and Nulls**
2. **Unpivoted Cuisine Columns** for better granularity
3. **Added a Conditional Column** → *Rating Band*
4. **Created Pivot Tables** to summarize:

   * Restaurant count by cuisine
   * Average rating by city
   * Rating band frequency

### ❓Why Excel First?

* Quick visual exploration
* Easy pivoting to identify early patterns
* Built intuition for what metrics matter (e.g., *Votes*, *Rating*, *Cuisines*)

---

## 🚀 Power BI Transition – Advanced Analysis

Excel was limited in interactivity and complex logic. We switched to **Power BI** for:

* Advanced **DAX-based KPI creation** (Rating Growth, Adjusted GPI)
* Interactive filters, drill-downs, and slicers
* Dashboard-style layout for **portfolio-quality storytelling**
* Data modeling and dynamic visuals

---

## 📈 Final Dashboard Includes:

### 1. **Summary Dashboard**

* Total restaurant count
* Rating Growth (Tier 4 vs Tier 1)
* Growth Potential Index (GPI)
* Recommended City for Expansion (based on GPI)
* Final insight panel (e.g., *“Quezon City” as best expansion target*)

### 2. **City Performance**

* Bar + line chart: Restaurant Count vs Avg Rating
* Top-N slicer for city filtering

### 3. **Pricing Tier Analysis**

* Distribution across Tier 1–4
* Avg. Rating vs Tier
* Insight: Higher tiers offer better satisfaction

### 4. **Service Breakdown**

* Cards and pie charts for Online Delivery, Table Booking
* Avg. Rating by service availability

### 5. **Votes & Ratings Analysis**

* Scatter plot with trendline
* Correlation analysis (r = \~0.31)
* Advanced: log scale suggestion + quadrant insight

### 6. **Adjusted GPI Model**

* Calculated using:
  `Adjusted GPI = Avg Rating × log(Votes + 1) ÷ City Level Count`
* Highlighted cities with **low penetration but high satisfaction**
* Final result selection **traceable** through supporting table

---

## 🏁 Key Takeaway

> The project combines Excel’s speed with Power BI’s depth to create a **fully interactive and data-driven restaurant intelligence solution**, identifying **where to expand**, **why**, and **how satisfaction aligns with service quality and pricing**.
