# Online-Bookstore-SQL-Project
I built a small SQL-based Online Bookstore database with tables for Books, Customers, and Orders. I wrote queries to check book details, customer records, revenue, stock, and monthly orders. I also created advanced analytical queries to track top-selling books, customer spending, and remaining inventory.

## 1. Project Overview
This project is a simple SQL-based Online Bookstore Database designed to store book information, customer details, and order transactions. It includes structured tables and analytical SQL queries to understand sales, inventory levels, and customer buying patterns.

---

## 2. Database & Table Design

### 2.1 Database Setup
- Created database: **OnlineBookstore**
- Built 3 main tables with proper keys and relationships.

### 2.2 Table Details

#### **1. Books Table**
- Stores Title, Author, Genre, Publish Year, Price, Stock  
- **Primary Key:** `Book_ID`

#### **2. Customers Table**
- Stores Name, Email, Phone, City, Country  
- **Primary Key:** `Customer_ID`

#### **3. Orders Table**
- Tracks every purchase: Order Date, Quantity, and Total Amount  
- **Foreign Keys:** `Customer_ID`, `Book_ID`

**Insight:**  
The tables form a clean relational structure to support inventory tracking, customer analysis, and sales management.

---

## 3. Basic SQL Queries & Insights

### 3.1 Book & Genre Queries
1. Retrieve all Fiction books  
2. Books published after 1950  
3. Distinct genres available

### 3.2 Customer Queries
4. Customers located in Canada  
5. Customers who ordered more than 1 quantity

### 3.3 Order & Inventory Queries
6. Orders from November 2023  
7. Total stock available  
8. Most expensive book  
9. Orders above $20  
10. Book with the lowest stock  
11. Total revenue generated  

**Insight:**  
These queries help track stock, analyze orders, and understand customer distribution.

---

## 4. Advanced SQL Analysis & Insights

### 4.1 Sales Analysis
12. Total books sold for each genre  
13. Total books sold by each author  
14. Most frequently ordered book  

### 4.2 Pricing & Genre Insights
15. Average price of Fantasy books  
16. Top 3 most expensive Fantasy books  

### 4.3 Customer Behavior
17. Customers with at least 2 orders  
18. Customer who spent the most  
19. Cities where customers spent more than $30  

### 4.4 Inventory Calculation
20. Stock remaining after fulfilling all orders  

**Insight:**  
These advanced queries help identify bestsellers, top customers, sales patterns, and inventory shortages.

---

## 5. Summary
This SQL project demonstrates:
- Database design  
- Table creation with relationships  
- Basic to advanced SQL querying  
- Real-world insights including sales trends, customer behavior, and stock monitoring  

It serves as a complete mini-database system for practicing SQL in a real-world scenario like an online bookstore.

---

## 📂 Files Included
- **Online bookstore project SQL.sql** – Full database setup + all queries

---

