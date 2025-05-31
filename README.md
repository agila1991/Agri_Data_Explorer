# Agri_Data_Explorer
# 🌾 Agriculture Data Analysis Project

This project focuses on analyzing agricultural production data across Indian states and districts using 
-> Power BI
-> SQL
-> Python
The analysis includes production trends, crop yield efficiency, district-level comparisons, and more, based on 50 years of data.

## 📊 Tools & Skills Used

- 🐍 Python (Pandas, Seaborn, Matplotlib).
- 🔎 SQL (MySQL Queries for Aggregation, Joins, Filtering).
- 📈 Power BI (Interactive Dashboards, DAX Queries, Visual Reports).
- 📂 Exploratory Data Analysis (EDA).
- 🧠 Data Cleaning and Preprocessing.
- 📌 Data Visualization & Insight Generation.

## 🧾 Project Highlights

### ✅ Key Analyses Performed

- **Top Producing States & Districts** for Rice, Wheat, Oilseeds, Cotton, etc.
- **Year-wise Trend Analysis** for crops like Sugarcane, Maize, and Millet.
- **Rice vs. Wheat Production Comparison** (last 50 years).
- **Yield Efficiency** analysis (e.g., Rice Yield in West Bengal Districts)
- **District-wise Correlation** between Area and Production for major crops.
- **5-Year Growth Rate** for Oilseed production across states.
- **Top 10 Wheat Production Years** in Uttar Pradesh.

## 📌 Sample Visuals

- 🌾 **Bar Charts**: Top 7 Rice Producing States, Groundnut Producting States.
- 🌱 **Line Charts**: Sugarcane Production Over 50 Years.
- 🌐 **Pie/Donut Charts**: Wheat Production by percentage of top 5 States.
- 📉 **Scatter Plots**: Impact of Area on Production (Rice, Wheat, Maize).
- 📍 **Stacked Bar Charts**: Crop Area Distribution Across Years.

## 🗃️ Dataset Information

- 50+ years of agricultural data from Indian states and districts.
- 16,146 rows and 80 columns.
- Fields include:
  - Year, State, District,state_code,District_code,
  - Crop-specific Area, Production, Yield
  - Fruit, Vegetable, oil seeds 

## 🧪 How to Run

### 🔹 Python
1. Run `agriculture_data.ipynb` for EDA and chart generation.
2. Use `generate_create_table_agriculture_data` to auto-create MySQL tables.
3. Insert cleaned data using Pandas-to-SQL inserts.

### 🔹 Power BI
1. Load the cleaned dataset ( Sql database).
2. Use provided Power BI DAX scripts to generate visuals.
3. Build interactive dashboards.

