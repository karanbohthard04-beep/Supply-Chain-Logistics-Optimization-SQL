# Supply Chain & Logistics Optimization using SQL

## 📌 Project Overview
This project focuses on analyzing logistics and supply chain performance data using **SQL queries within Python**. By investigating transactional records, the project identifies key operational bottlenecks such as high rates of late deliveries and risk areas for fraud, providing actionable insights for supply chain managers.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Database Engine:** SQLite (via sqlite3)
- **Libraries:** Pandas, Matplotlib, Seaborn

## 🔍 Key SQL Analysis Performed
1. **Delivery Status Breakdown:** Evaluated the overall health of logistics operations by grouping orders by shipping status.
2. **Regional Inefficiencies:** Used aggregations (`COUNT`, `GROUP BY`, `ORDER BY`) to extract the top 5 global regions suffering from the highest number of 'Late Deliveries'.

## 📈 Business Insights & Actions
- **Logistics Bottlenecks:** Specific regions identified with heavy late delivery counts require shipping carrier renegotiations or local warehouse optimizations.
- **Data-Driven Operations:** Demonstrates how embedded SQL can be leveraged directly within analytical notebooks to handle larger datasets seamlessly without heavy enterprise server infrastructure.
