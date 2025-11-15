# 📚 Online BookStore – SQL Project  

## 📌 Overview  
The **Online BookStore** project is a relational database system built using **PostgreSQL** to manage books, customers, and orders efficiently.  
This project simulates a real-world bookstore backend where users can browse books, place orders, and analyze sales, stock, and customer data.  

The system supports:  
- Book inventory management  
- Customer records  
- Order processing  
- Sales & stock analytics  
- Advanced SQL insights  

---

## 🛠️ Tech Stack  
- 🗄️ **PostgreSQL** – Database & query engine  
- 🧹 **SQL (DDL + DML + Joins + Aggregations)**  
- 📁 **CSV File Imports** (Books, Customers, Orders)  
- 📝 **Data Modeling** – 3 interconnected tables  
- 🔗 **Foreign Key Constraints** for referential integrity  

---

## 🧱 Database Structure  

### **1️⃣ Books Table**  
Stores information about available books.  
Fields → `Book_ID`, `Title`, `Author`, `Genre`, `Published_Year`, `Price`, `Stock`

### **2️⃣ Customers Table**  
Contains customer details.  
Fields → `Customer_ID`, `Name`, `Email`, `Phone`, `City`, `Country`

### **3️⃣ Orders Table**  
Captures order transactions.  
Fields → `Order_ID`, `Customer_ID`, `Book_ID`, `Order_Date`, `Quantity`, `Total_Amount`  
Dependencies → References **Customers** & **Books** tables.

---

## 📥 Data Import  
Data is imported from CSV files using `COPY` command:  
- Books.csv  
- Customers.csv  
- Orders.csv  

---

## 🔍 Key SQL Functionalities Implemented  

### ✅ **Basic Queries**  
- Retrieve books by genre  
- Filter books by year of publication  
- Find customers by country  
- Show orders for a specific month  
- Total stock available  
- Most expensive and lowest stock book  
- Customers with quantity > 1  
- Orders above a certain amount  

### ✅ **Advanced Queries**  
- Total books sold per genre  
- Average price of books by genre  
- Customers placing at least 2 orders  
- Most frequently ordered book  
- Top 3 expensive books by genre  
- Quantity sold by each author  
- Cities with high-spending customers  
- Customer who spent the most  
- Stock remaining after orders  

---

## 📊 Insights From the Database  

### **📘 Books Insights**  
- Wide variety of genres such as **Fiction, Fantasy, Thriller**, etc.  
- Books range across multiple authors & price points.  
- You can track best-sellers, low-stock books, and genre popularity.

### **🧑‍🤝‍🧑 Customer Insights**  
- Customers spread across various cities & countries.  
- Identify high-paying or frequent-order customers.

### **💰 Order & Sales Insights**  
- Total revenue generated  
- Most purchased books and genres  
- Peak purchasing month (e.g., November 2023 queries)  
- Track sales by authors and book categories  

---

## ⭐ Sample Insights From SQL Queries  
Based on the provided SQL logic, the project gives insights such as:  

- **Total Book Stock** available in the store  
- **Most Expensive Book** and **Least Stock Book**  
- **Genres generating highest sales**  
- **Top customers based on spending**  
- **Remaining stock after fulfilling all orders**  
- **Author-wise total books sold**  

---

## 🧾 Example Use Cases  
This Online BookStore database can be used for:  
- Inventory management  
- Customer segmentation  
- Sales analytics  
- Best-seller prediction  
- Order tracking and fulfillment  
- Author performance insights  
- Genre popularity trends  

---

## 📸 Project Files  
- `Books.csv` – Book inventory  
- `Customers.csv` – Customer database  
- `Orders.csv` – Order transactions  
- `Day 30 - Final Assignment.sql` – Full SQL script (DDL + DML + Queries)

---

## 👨‍💻 Author  
**Sujal Taleti**  
Online BookStore Database – PostgreSQL Final Assignment  

