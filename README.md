# 🌍 Airbnb Pricing Analysis Across 10 European Cities

## 📝 Overview
This project analyzes **Airbnb pricing data** from 10 major European cities to uncover:
- Patterns and trends in pricing.
- Insights about guest satisfaction.
- Geographical factors impacting listing prices.

Using **Python** for Exploratory Data Analysis (EDA) and **Power BI** for visualization, the project explores the determinants of Airbnb pricing and provides actionable insights.

---

## 🎯 Objectives
### **1. Understand Pricing Determinants**
- Analyze the effect of **room type**, **cleanliness**, **location**, and **host status** on pricing.
- Explore how pricing patterns vary across cities.

### **2. Compare Weekday vs Weekend Pricing**
- Identify differences in pricing trends between weekdays and weekends.

### **3. Perform Geographical Analysis**
- Investigate the impact of proximity to city centers on pricing.
- Map high-demand and high-priced areas using **geospatial data**.

### **4. Evaluate Guest Satisfaction**
- Examine the relationship between **guest satisfaction ratings** and pricing.
- Assess whether **Superhosts** charge higher prices.

---

## 🛠️ Tools and Technologies
- **Dataset**: Airbnb listings data for 10 European cities (raw and cleaned versions).
- **Programming Language**: Python
- **Libraries**:
  - `Pandas` and `NumPy`: Data manipulation and analysis.
  - `Matplotlib` and `Seaborn`: Data visualization.
  - `Folium`: Geospatial visualization.
- **Business Intelligence Tool**: Power BI

---

## 📂 Files in This Repository
### **Datasets**
1. `airbnb_combined.csv`: Raw dataset combining Airbnb listings data from 10 cities.
2. `airbnb_cleaned.csv`: Cleaned dataset used for analysis and dashboard creation.

### **Python Analysis**
- `airbnb_price.ipynb`: Jupyter Notebook that includes:
  - Data cleaning.
  - Descriptive analysis.
  - Visualizations (e.g., price distribution, room type vs revenue).

### **Power BI Dashboard**
- `airbnb_sales_dashboard.pbix`: Interactive Power BI dashboard 

---

## 🔍 Key Insights
### **1. Pricing Determinants**
- **Room Types**:
  - Entire homes/apartments generate the highest revenue ($10.6M), followed by private rooms ($3.8M) and shared rooms ($0.1M).
  - Average prices:
    - Entire homes/apartments: $324
    - Private rooms: $205
    - Shared rooms: $144
- **City-Level Insights**:
  - Amsterdam has the highest average price ($573), followed by Paris ($392) and London ($362).
  - Athens ($151) and Budapest ($176) offer the most affordable options.

---

### **2. Weekday vs Weekend Pricing**
- Weekend revenue ($7.4M) is slightly higher than weekday revenue ($7.0M).
- Average prices remain consistent across weekdays and weekends.

---

### **3. Geographical Analysis**
- High-priced listings cluster near city centers, particularly in Amsterdam, Paris, and London.
- Listings farther from the center tend to be more affordable.

---

### **4. Guest Satisfaction**
- **Higher guest satisfaction correlates with higher prices**, especially for ratings above 90.
- Superhosts account for **26.8% of listings**, commanding higher prices compared to non-Superhosts.

---

## 📊 Visualizations
### Python EDA
1. **Price Distribution**: Histogram showing frequency of listing prices.
2. **Room Type Analysis**: Bar chart comparing revenue by room type.
3. **City-wise Pricing**: Boxplot showing price distributions across cities.
4. **Guest Satisfaction vs Pricing**: Scatter plot highlighting the correlation between satisfaction ratings and pricing.

### Power BI Dashboard
- **KPIs**:
  - Total Listings, Average Price, Highest-Priced City, and Total Revenue.
- **Room Type vs Revenue**: Bar chart visualizing revenue contributions.
- **Day Type vs Revenue**: Trends in weekday vs weekend revenue.
- **Superhost Proportion**: Pie chart showing the proportion of Superhosts.
- **Geospatial Insights**: Interactive map displaying listings by location and price.

---



