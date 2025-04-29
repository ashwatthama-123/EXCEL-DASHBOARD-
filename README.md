# ☕Coffee Shop Sales Analysis Dashboard Plan (Excel + Power Query)📊

**1. Data Preparation (Power Query Stage)**

a. Import sales datasets (could be CSVs, Excel files, or database connections).

b. Cleanse the data:

c. Remove duplicates.

d. Standardize date and time formats.

e. Split timestamp into Date, Hour, and Day of Week fields.

f. Normalize product names and categories.

g. Create calculated columns:

h. Sales Amount = Quantity × Unit Price

i. Hour of Sale = Extract hour from Timestamp, Month = Extract month, Store Location = ensure clean grouping

j. Create lookup tables if needed (for locations, products, size categories).

---
**2. Key Dashboard Visualizations 📈**

a) 🕒 Quantity Orders by Hour (Peak Time Analysis) Chart: Bar or Line Chart Insight: 📊 Plan staffing for busy times!

b) 💲 Price Distribution Across Product Categories Chart: Box Plot / Column Chart Insight: 🎯 Find high-margin or underpriced products.

c) 🥤 Size Distribution (Customer Preference) Chart: Pie Chart or Stacked Column Chart Insight: 📈 Focus promotions on popular drink sizes.

d) ⭐ Top 10 Products Sold Chart: Horizontal Bar Chart or Table Insight: 🚀 Highlight hero products for bundling or marketing.

e) 🏪 Foot Traffic Analysis Across 3 Locations Chart: Line or Clustered Column Chart Insight: 🧠 Tailor marketing to location performance.

f) 📅 Trend Analysis Over Days & Months Chart: Line or Area Charts (filterable by time) Insight: 📆 Spot seasonal trends & campaign impacts.

---
**3. Interactive Features Slicers 🧩**

Date range (calendar) Store location Product category Size Dynamic Titles (based on slicer selections). Drill-downs (e.g., Year > Quarter > Month > Day).

---
**4. Advanced Techniques🧠**

Dynamic Measures (using PivotTables):

=SUMIFS(Sales, Date, [Selected Period])

=AVERAGEIFS(Price, Product Category, [Selected Category])

Power Query Auto-Refresh 🔄 (manual or scheduled).

Key Metrics:

💰 Total Revenue

🛒 Total Orders

🧾 Average Sale per Customer

🏪 Customer Traffic per Location

---
**5. Storytelling Angle📚**

Use meaningful section headers like:

"When Are Our Peak Times?" 🕒

"Which Products Drive Our Revenue?" 💰

"How Do Different Locations Perform?" 🏪

"Customer Size Preferences Over Time" 🥤

*🔔 Goal: Made the dashboard not just informative, but actionable and recommendation-driven for business!*
