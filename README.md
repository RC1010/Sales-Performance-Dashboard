# Sales-Performance-Dashboard
📊 Power BI interactive sales dashboard analyzing customer demographics (Age/Gender) and product performance to deliver actionable business insights.

# 📊 Consumer Sales & Demographics Performance Dashboard
<img width="1483" height="835" alt="Screenshot 2026-05-31 153906" src="https://github.com/user-attachments/assets/478335f4-7732-447a-8eee-7b2940994a27" />

## 📝 Project Overview
An interactive, high-contrast Power BI dashboard designed to analyze retail sales performance across product categories and customer demographics. This project transforms raw transactional data into actionable executive insights, shifting focus from raw revenue values to true customer transaction volumes to optimize marketing strategy.

## 🛠️ Tech Stack & Skills
* **Tool:** Power BI Desktop
* **Data Transformations:** Power Query (Data cleaning, type casting, and column profiling)
* **Visual Layout:** Custom dark-mode theme designed for quick scanning and executive readability.

## ⚙️ Key Visual & Technical Features
* **Interactive Multi-Demographic Filtering:** Integrated drop-down slicers for Month, Product, and Age to allow deep-dive, customized analysis of the consumer base.
* **Executive KPI Cards:** High-level summary cards tracking macro business health metrics: Total Orders (3K), Average Order Value ($180), and Total Revenue ($456K).
* **Time-Series Trend Mapping:** A continuous area chart tracking Amount Earned Over Time, designed to easily spot seasonal peaks and operational shifts.
* **Categorical Volume & Value Profiling:** Contrasts category metrics using a distributed line plot alongside a horizontal bar chart to track performance differences across Electronics, Clothing, and Beauty.
* **Granular Transaction Audit Log:** A raw data matrix table at the bottom, mapping individual purchases by Price per Unit, Total Amount, Date, Gender, and Age for line-item transparency.
* **Balanced Demographics Breakdown:** A high-contrast donut chart detailing the total buyer ecosystem split (49% Male vs. 51% Female).

## 💡 Executive Key Takeaways & Insights
* **Volume vs. Value Leadership:** While **Electronics** generated the highest overall financial order value ($62K), tracking transaction volumes reveals highly consistent customer engagement across all product categories.
* **Demographic Volume Mix:** Analyzing customer transaction records per category reveals a highly balanced consumer ecosystem that closely mirrors the overall database split of **51% Male and 49% Female** buyers.
* **Peak Revenue Seasonality:** Total revenue experienced major upward surges in **April 2023** and **October 2023**, representing the highest-performing sales periods of the fiscal year.

## 📂 Dataset Architecture
The dashboard processes flat transactional data utilizing the following columns:
* `Date` (`Year`, `Month`, `Day`) - Time-series trend mapping
* `Age` & `Gender` - Customer demographic segmentation
* `Product` - Category performance mapping
* `Quantity`, `Price per Unit`, & `Total Amount` - Volume and financial metrics

## 🚀 How to View the Project
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop**.


