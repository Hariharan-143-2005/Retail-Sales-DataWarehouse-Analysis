# 🧠 Retail Sales Data Warehouse Analytics

A complete SQL project that performs data warehouse analytics for a retail sales system using a star schema architecture.

## 📊 Description

This project demonstrates advanced SQL techniques for analyzing retail business performance. It uses a star schema with:
- `fact_sales`: sales transactions
- `dim_customers`: customer demographic details
- `dim_products`: product and category information

All analysis is executed in SQL Server using views, CTEs, window functions, and aggregations.

---

## 📁 Data Schema: `gold` (schema)
- **`fact_sales`**: Sales transactions with price, quantity, and order data.
- **`dim_customers`**: Customer details like name, birthdate, country, gender.
- **`dim_products`**: Product metadata including category, subcategory, and cost.

---

## 📌 Key Analyses

- Total Sales, Orders, and Product Counts
- Category-wise Revenue & Product Distribution
- Country & Gender-based Customer Analysis
- Yearly & Monthly Sales Trends
- Customer Segmentation: VIP, Regular, New
- Product Segmentation: High, Mid, Low Performer
- Created Views:
  - `customer_report`
  - `report_products`

---

## 💡 Technologies Used

- SQL Server
- T-SQL (CTEs, Window Functions, Views)
- Data Modeling (Star Schema)
- Optional: Power BI/Tableau (for dashboarding)

---

## 🚀 How to Use

1. Execute the `.sql` file in a SQL Server environment.
2. Make sure schema `gold` and base tables exist or create them.
3. Use the views `gold.customer_report` and `gold.report_products` for reporting or dashboarding.

---

## 📬 Author

- **Hariharan V** – [LinkedIn](https://www.linkedin.com/) *(update with your real link)*

