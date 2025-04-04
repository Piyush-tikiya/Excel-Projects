# Excel-Bike Sale Interactive Dashboard
Bike Sales Dashboard – Breakdown of Components & KPIs
This Excel-based interactive dashboard is designed for analyzing bike sales data, tracking income distribution, customer demographics, and purchase trends.

-- **Below is a breakdown of how it was created and the key metrics used.**
## Dataset Used -
<a href = "https://github.com/Piyush-tikiya/Excel-Projects/blob/main/Bike%20Sale.xlsx"> Dataset View </a>

## Dashboard View
<a href = "https://github.com/Piyush-tikiya/Excel-Projects/blob/main/Bike%20sale%20dashboard.png"> Dashboard View </a>

 **Features & Components Used**
![Bike sale dashboard](https://github.com/user-attachments/assets/b21f0a8f-a2c6-43a2-a1a8-fe64e8facf50)

1️⃣ **Data Source & Processing**

Raw data stored in an Excel sheet (bike_buyers).

Pivot Tables used to summarize data.

Power Query (optional) for data cleaning and transformation.

2️⃣ **Dashboard Elements**

Slicers (Filters): Used to filter data dynamically based on Gender, Marital Status, and Education.

Pivot Charts & Graphs: Visual representation of key performance indicators.

📈**Key Performance Indicators (KPIs) & Metrics**
✅ Average Income

Formula: =AVERAGE(INCOME_RANGE)

Displays the average income of bike buyers.

✅**** **Income Distribution by Gender**

Bar Chart representing total income earned by male vs. female buyers.

Formula: =SUMIFS(INCOME_RANGE, GENDER_COLUMN, "Male/Female")

✅ **Distance vs. Region Count**

Doughnut Chart showing how far customers travel to purchase bikes.

Data grouped using Pivot Table.

✅ **Bike Purchases by Age Group**

Horizontal Bar Chart comparing purchases made by different age brackets.

Data sourced from a Pivot Table.

✅ **Sum of Cars vs. Count of Purchased Bikes (Line Chart)**

X-Axis: Different job categories (Clerical, Management, Manual, etc.).

Y-Axis: Count of Cars Owned vs. Bikes Purchased.

Uses COUNTIFS() and SUMIFS() to calculate values.

📌 **Key Formulas & Functions Used**
🔹 SUMIFS – =SUMIFS(INCOME_RANGE, GENDER_COLUMN, "Male") (Calculates total income based on gender).
🔹 COUNTIFS – =COUNTIFS(AGE_GROUP_COLUMN, "Middle Age") (Counts buyers in a specific age group).
🔹 AVERAGEIF – =AVERAGEIF(EDUCATION_COLUMN, "Graduate", INCOME_RANGE) (Finds the average income of buyers with a graduate degree).
🔹 INDEX-MATCH / XLOOKUP – Used for fetching data dynamically in dropdown selections.
🔹 Pivot Tables & Charts – Aggregates and visualizes sales, customer demographics, and financial trends.
🔹 Slicers – Allows users to filter the dashboard dynamically.

**-** Conclusion****
This Bike Sales Dashboard is built using a combination of Pivot Tables, Slicers, Excel formulas, and Data Visualization. It helps businesses track customer behavior, sales performance, and financial insights efficiently.
