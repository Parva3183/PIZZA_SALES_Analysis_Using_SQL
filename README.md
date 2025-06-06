# 🍕 Pizza Sales Data Analysis using SQL

## 📌 Project Overview

The Pizza Sales Data Analysis project is a SQL-based data analysis initiative aimed at uncovering valuable business insights for a pizza restaurant. By working with real-world-like sales data, the project demonstrates how SQL can be used to answer critical business questions such as identifying top-selling pizzas, revenue trends, popular order times, and customer preferences.

The dataset contains structured information about customer orders, pizza types, categories, sizes, pricing, and timestamps. Through this project, I applied various SQL techniques — from basic SELECT statements to advanced window functions — to analyze sales performance and generate actionable insights for decision-making.

This hands-on project enhances skills in data extraction, manipulation, joining, grouping, and aggregating. It simulates the kind of analysis a business analyst or data analyst would perform to support marketing, operations, and strategic planning.

---

## 📂 Dataset Description

The dataset includes the following tables:

- **orders**: Order ID, date, and time of the order.
- **order_details**: Mapping of orders to pizza IDs and quantities.
- **pizzas**: Price, size, and ID of each pizza sold.
- **pizza_types**: Name, category (Classic, Veggie, Supreme, etc.), and ingredients of each pizza.

---

## 🎯 Business Questions Solved

### ✅ Basic-Level Queries
- Retrieve the total number of orders placed
- Calculate the total revenue from pizza sales
- Identify the highest-priced pizza
- Identify the most common pizza size ordered
- List the top 5 most ordered pizza types and their quantities

### 🔄 Intermediate-Level Queries
- Join necessary tables to find total quantity per pizza category
- Determine the hourly distribution of orders
- Join and group data to get category-wise pizza distribution
- Group orders by date and calculate average pizzas ordered per day
- Identify the top 3 pizza types by total revenue

### 📊 Advanced-Level Queries
- Calculate percentage contribution of each pizza type to total revenue
- Analyze cumulative revenue growth over time
- Determine the top 3 revenue-generating pizzas in each category

---

## 🧠 SQL Concepts Applied

- **Basic SQL**: SELECT, WHERE, GROUP BY, ORDER BY, LIMIT
- **Aggregate Functions**: COUNT(), SUM(), MAX(), AVG()
- **Joins**: INNER JOIN, LEFT JOIN for multi-table queries
- **Date & Time Functions**: EXTRACT(), TO_CHAR(), DATE_TRUNC()
- **Subqueries**: Nested SELECT statements for filtering and ranking
- **Window Functions**: SUM() OVER(), ROW_NUMBER() OVER() for cumulative revenue and ranking
- **Percentage Calculations**: Revenue share per pizza type

---

## 💡 Key Insights

- The restaurant's highest sales occur during evening hours and weekends
- Classic and Supreme pizzas are the most popular categories
- Medium and large sizes are the most preferred by customers
- A few pizza types account for the majority of revenue — useful for targeted marketing
- Cumulative revenue trends show consistent performance with seasonal spikes

---

## 🛠 Tools & Technologies Used

- **SQL Language**
- **PostgreSQL / MySQL / SQLite** *(mention the one you used)*
- **DB Browser for SQLite / pgAdmin / MySQL Workbench** *(whichever was your SQL environment)*

---

## 🚀 How to Run This Project

### 1. **Clone the Repository**


git clone https://github.com/yourusername/pizza-sales-sql-analysis.git
cd pizza-sales-sql-analysis

---

## 🤝 Acknowledgments

This project was created as part of my journey to strengthen data analysis skills using SQL.

---

## 📬 Contact

If you have any questions or feedback, feel free to connect with me on [LinkedIn]( https://www.linkedin.com/in/parvashah3183) or email me at parvashah3183@gmail.com.
