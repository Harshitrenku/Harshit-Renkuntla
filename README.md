# 📊 Reliance Smart Superstore - Power BI Sales Performance Dashboard

This Power BI project presents a **Retail Sales Performance Dashboard** for a fictional store, **Reliance Smart Superstore**. The dashboard is designed to showcase analytical insights across multiple dimensions such as revenue, profit, returns, product brand, geography, and state-wise performance.

#Report View

<img width="766" alt="Image" src="https://github.com/user-attachments/assets/1768fe59-b21c-4e1e-b3f8-f39bbfba6acd" />

----

<img width="755" alt="Image" src="https://github.com/user-attachments/assets/5b7ac922-fb9a-4322-ac28-2e19a44335c0" />

## 🧠 Key Features & Insights

### ✅ KPIs Compared with Previous Month:
- **Revenue:** ₹120.16K vs. goal of ₹113.79K (+5.6%)
  
  <img width="203" alt="Image" src="https://github.com/user-attachments/assets/58ac37ed-c5a8-482a-a372-79844eddfad1" />

- **Profit:** ₹71.68K vs. goal of ₹67.87K (+5.61%)
  
  <img width="211" alt="Image" src="https://github.com/user-attachments/assets/2ca4909e-a924-4cc4-878a-b9506a4a1029" />

- **Returns:** 496 vs. goal of 563 (⬇️ 11.9%)
  
  <img width="207" alt="Image" src="https://github.com/user-attachments/assets/11f84d56-afa5-42d2-99dc-1672d3252e09" />

These KPI visuals leverage built-in indicators and sparklines to provide a quick comparative glance against previous month targets.

---

## 📌 Visual Highlights

- **KPI Cards:** Used to visualize Revenue, Profit, and Returns vs. previous month using conditional formatting and data bars.
- **Product Brand Wise Table:** Detailed matrix showing transactions, quantity, revenue, and profit by brand.
- **Geographic Map:** Store performance mapped across different geographies using the ArcGIS visual.
- **State-wise Tree Map:** Transactional distribution across US and Mexican states.
- **Trendlines:** Integrated line charts to show historical growth trend for revenue, profit, and returns.

---

## 🧮 DAX Formulas Used

This report demonstrates extensive usage of **DAX expressions** to derive calculated metrics, time intelligence, and dynamic KPIs.

### Time Intelligence:
- `PREVIOUSMONTH()`
- `DATESINPERIOD()`
- `TOTALYTD()`, `TOTALQTD()`

  <img width="421" alt="Image" src="https://github.com/user-attachments/assets/d7bd4375-e2bd-4a62-89cb-dd9274169e21" />

### Filter & Context Functions:
- `CALCULATE()`
- `ALL()`
- `FILTER()`

### Aggregations & Logical Operations:
- `SUMX()`, `RELATED()`
- `DISTINCTCOUNT()`, `COUNTA()`
- `MAX()`, `MIN()`

### User-specific Analytics:
- `USERPRINCIPALNAME()` – to make the report dynamic per logged-in user (ideal for role-level security scenarios)

---

## 🧰 Tools & Technology

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query Editor**
- **Microsoft Bing Maps Integration**

---

## 💡 Purpose

This project was developed as a **portfolio piece** to demonstrate proficiency in:
- Building professional BI dashboards
- Applying advanced DAX logic
- Performing trend analysis, forecasting, and comparative reporting
- Presenting meaningful business insights in a clean, interactive format

---

## 📎 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Explore various visuals, slicers, and filters.
4. Review the DAX measures from the "Modeling" pane to understand the logic behind each metric.

---

## 📣 Feedback

If you have suggestions or feedback, feel free to open an issue or connect with me via www.linkedin.com/in/harshit1988
