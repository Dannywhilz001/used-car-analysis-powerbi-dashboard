# 🚗 Used Car Analysis Dashboard

### 📊 Overview
The **Used Car Analysis Dashboard** is an interactive Power BI project designed to explore and visualize key insights from a used car dataset.  
It provides a detailed overview of **brand performance**, **pricing trends**, **ownership history**, and **insurance coverage**, enabling better decision-making for both buyers and dealers in the automotive industry.

This project demonstrates the use of **Power BI for data analytics and storytelling**, combining visual design, DAX calculations, and data modeling.

---

## 🎯 Business Objective
The goal of this project is to analyze factors that influence **used car pricing and market trends**.  
By examining attributes such as **brand**, **model year**, **service history**, and **insurance coverage**, this dashboard helps identify patterns that impact resale value and demand.

**Key questions answered:**
- Which car brands have the highest average and total resale values?  
- How does ownership history affect car pricing?  
- What is the impact of transmission type and insurance coverage on sales?  
- How do different engine types and colors influence buyer preferences?

---

## 🧩 Dataset Information
The dataset includes historical records of used cars and their attributes such as:
- **Brand**
- **Model Year**
- **Engine Type**
- **Color**
- **Service History**
- **Insurance Coverage**
- **Transmission Type**
- **Ownership Count**
- **Car Price**

Data was prepared and cleaned using **Power Query** and modeled in **Power BI Desktop**.

---

## ⚙️ Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data visualization and dashboard creation |
| **Microsoft Excel / CSV** | Raw data preprocessing and transformation |
| **DAX (Data Analysis Expressions)** | Creation of KPIs and calculated metrics |
| **Power Query** | Data cleaning and modeling |

---

## 📈 Key Metrics
| Metric | Description |
|--------|--------------|
| **Total Price (K)** | Sum of all used car prices across brands |
| **Average Price (K)** | Mean resale value across brands |
| **Ownership History** | Average number of previous owners per brand |
| **Insurance Coverage** | Count of cars with active insurance |
| **Transmission Type Analysis** | Ratio of automatic vs manual vehicles |

---

## 🖥️ Dashboard Insights

📸 **Screenshot:**  
![Used Car Dashboard](https://ibb.co/9msRN4nZ)

### 🔹 Visual Components
1. **Brand Filter**
   - Allows users to filter insights by car manufacturer (e.g., BMW, Hyundai, Toyota).

2. **Ownership History Gauge**
   - Shows the average ownership count across cars.

3. **Total & Average Price Gauges**
   - Displays both total and mean car prices segmented by brand.

4. **Service Records Table**
   - Summarizes car attributes like service history, engine type, and color.

5. **Insurance & Transmission Analysis**
   - Highlights the relationship between transmission type (Automatic/Manual) and insurance status.

6. **Model Year Filter**
   - Enables exploration of pricing and service trends across different years.

---

## 🧮 Example DAX Measures

```DAX
-- Average Car Price
Average Car Price = AVERAGE(UsedCars[Price])

-- Total Car Price
Total Price = SUM(UsedCars[Price])

-- Ownership Count
Total Owners = COUNTROWS(UsedCars[Owner_ID])

-- Average Ownership History
Average Ownership = AVERAGE(UsedCars[Ownership_History])
````

---

## 💡 Insights & Recommendations

* **BMW and Toyota** consistently show **higher total and average prices**, reflecting brand reliability and resale strength.
* Cars with **complete service history** and **automatic transmission** tend to have **better resale values**.
* **Insurance coverage** positively correlates with pricing, as insured cars are perceived as lower risk.
* Vehicles with **fewer previous owners** command higher resale prices.
* Neutral colors like **white and silver** are most common and often have slightly higher resale rates.

---

## 🚀 How to Use

1. Download this repository or clone it:

   ```bash
   git clone https://github.com/Dannywhilz001/used-car-analysis-powerbi-dashboard.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use filters (Brand, Model Year, Transmission) to interact with the dashboard.
4. Explore relationships between car features and pricing trends.

---

## 🗂 Folder Structure

```
📦 Used-Car-Analysis-PowerBI-Dashboard
 ┣ 📊 USED CAR ANALYSIS DASHBOARD.pbix
 ┣ 🖼️ used car analysis.PNG
 ┗ 📘 README.md
```

---

## 🧠 Learning Outcomes

* Gained expertise in **Power BI data modeling and visualization**.
* Used **DAX measures** to calculate KPIs and performance metrics.
* Designed a **business-oriented dashboard** for quick insights.
* Strengthened understanding of **automotive market trends** and **data storytelling**.

---

## 🏁 Conclusion

The **Used Car Analysis Dashboard** provides valuable insights into the used car market, enabling stakeholders to:

* Identify high-value brands,
* Analyze resale trends, and
* Make informed decisions based on data-driven insights.

This project demonstrates the power of **Power BI** in building real-world analytics solutions for the **automotive industry**.

---

## 👨‍💻 Author

**Oladotun Olawale**

📧 Email: oladotunolawale29@yahoo.com

🔗 LinkedIn: http://www.linkedin.com/in/oladotun-olawale

💼 Portfolio: https://github.com/Dannywhilz001
## 🏷 GitHub Topics

`#powerbi` `#data-analytics` `#dashboard` `#automotive` `#used-cars` `#data-visualization` `#dax` `#excel` `#business-intelligence`
