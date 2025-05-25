
# 📊 Coffee Shop Sales Dashboard – Power BI & SQL Analysis

This project presents a comprehensive sales analysis for a coffee shop, using Power BI for dashboard visualizations and MySQL for data preprocessing and querying.

---

## 🔍 Project Highlights

- **Data Source**: Sales data from `Coffee Shop Sales.xlsx`
- **Tools Used**: Power BI, MySQL, and Excel
- **Objective**: To derive insights from monthly and daily coffee shop sales and help stakeholders make data-driven decisions.

---

## 📈 Dashboard Features

- **📆 Calendar Heatmap**: Dynamic view of daily sales, color-coded by volume
- **📊 Monthly Trends**: Total Sales, Orders, Quantity – including month-over-month differences
- **🕐 Time Analysis**: Sales by Day & Hour, Weekday vs. Weekend
- **🏪 Store Location Performance**: MoM growth per location
- **📈 Daily Sales Chart**: With average benchmark line
- **📦 Product Category Analysis**
- **🏆 Top 10 Products by Sales**

---

## 🧰 SQL-Based Data Transformation

- Converted `transaction_date` and `transaction_time` to appropriate formats
- Renamed and cleaned column headers
- Created queries for:
  - Monthly summaries
  - Daily metrics
  - Category-level and time-based breakdowns
  - Top-selling product lists

> SQL queries are documented in the `COFFEE-SALES.pptx` file.

---

## 🖼️ Dashboard Screenshot
<img width="621" alt="coffee-sales-ss" src="https://github.com/user-attachments/assets/5e64d043-40e6-41b7-a1f8-e77dace6835b" />


---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/coffee-shop-sales-dashboard.git
   ```

2. Open the Power BI file:
   - Launch Power BI Desktop
   - Open `COFFEE_SHOP_SALES.pbix`

3. Review SQL Queries:
   - Open `COFFEE-SALES.pptx` to see all SQL logic used for transformation

---

## 📂 Files Included

| File Name                | Description                              |
|--------------------------|------------------------------------------|
| `Coffee Shop Sales.xlsx` | Raw transactional sales data             |
| `COFFEE_SHOP_SALES.pbix` | Power BI dashboard                       |
| `COFFEE-SALES.pptx`      | SQL queries and analysis documentation   |

---

## 🙌 Acknowledgments

- Data design inspired by real-world retail sales reporting
- Built as a self-project for portfolio and learning
