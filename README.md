# Olist Sales & Logistics Analytics — Power BI Project

This repository contains my end-to-end **Power BI analytics project** based on the public Olist e-commerce dataset.  
The goal was to build a complete BI solution — from data ingestion to interactive dashboards — using best practices in **data modeling, ETL, DAX, and UX/UI design**.

---

## 📊 Project Overview

This project was created as part of a BI training program.  
I received multiple raw CSV datasets related to **orders, products, customers, sellers, payments, reviews and geolocation** along with a business task description.  

The analytical solution includes:

- ⭐ A clean **semantic data model** (star schema)  
- ⭐ ETL in **Power Query**  
- ⭐ Custom KPIs in **DAX**  
- ⭐ Four interactive dashboards (Sales, Logistics, Payments, Reviews)  
- ⭐ Consistent UX/UI design with navigation, buttons, slicers and drill-down  

---

## 📁 Data Sources

The project is based on 9 official Olist CSV datasets:

- `olist_customers_dataset.csv`
- `olist_geolocation_dataset.csv`
- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`
- `olist_products_dataset.csv`
- `olist_sellers_dataset.csv`
- `product_category_name_translation.csv`

All source files can be downloaded here:

👉 **Source datasets (CSV):**  
https://drive.google.com/drive/folders/1HLPsoNNfYWFD-h27aKe48EWF1KauExxj

---

## 📂 Power BI File (.pbix)

The complete Power BI project, including the data model, transformations, DAX logic and dashboards, is available here:

👉 **Power BI report (`Nechaeva_BI.pbix`):**  
https://drive.google.com/file/d/1hysYv7YeqqW3cIA8Pjl_4OJH9xfbAmAV/view?usp=sharing

---

## 🧱 Data Model (Star Schema)

The data model follows a classic star design:

### **Fact tables**
- Fact Orders  
- Fact Order Items  
- Fact Payments  
- Fact Reviews  

### **Dimension tables**
- Dim Customers  
- Dim Products  
- Dim Sellers  
- Dim Geography  
- Dim Date  

Power Query was used to:
- clean and normalize fields  
- fix data types  
- create product category groups  
- create denormalized order stages for the sales funnel  
- generate a proper Date dimension  

---

## 🧮 DAX Metrics

Key measures include:

### **Sales KPIs**
- Revenue  
- Orders count  
- Average Check  
- Leads  
- Conversion rate  
- YoY metrics  

### **Logistics KPIs**
- On-time delivery rate  
- Average freight cost  
- Average order cycle time  
- Average processing time  

### **Payments KPIs**
- Payment status segmentation (paid / underpaid / overpaid)  
- Payment methods distribution  
- Installment groups  

### **Reviews KPIs**
- Average review score  
- Review volume dynamics  
- Score vs. Average check correlation  

---

## 📈 Report Pages (Dashboards)

The project includes **4 main dashboards**, each designed with a unified color theme and navigation menu.

### 1️⃣ **Sales Dashboard**
- Revenue & Leads trends  
- Sales funnel (Created → Approved → Shipped → Delivered)  
- Average check & YoY view  
- Map of orders  

### 2️⃣ **Logistics Dashboard**
- Freight analytics  
- Delivery performance  
- Processing & order cycle time  
- Product size categories (S–XXL)  

### 3️⃣ **Payments Dashboard**
- Cash balance  
- Delivery amount  
- Installment segmentation  
- Payment methods distribution  

### 4️⃣ **Reviews Dashboard**
- Review score trend  
- Score vs. average check  
- Number of customers with reviews  
- Map of review locations  

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** (modeling, DAX, visualization)  
- **Power Query (M)** for ETL  
- **DAX** for metrics and business logic  
- **OpenStreetMap** / Bing for map visuals  
- **Google Drive** for large file storage  

---

## 🚀 How to Use

1. Download the `.pbix` file from Google Drive  
2. Download the CSV dataset folder  
3. Open the Power BI report  
4. Update file paths if necessary (Transform Data → Data source settings)  
5. Refresh the model  

---

## 🧑‍💼 Author

**Polina Nechaeva**  
Data & Business Intelligence Analyst (Power BI / SQL / DAX / Python)  
Germany  

🔗 GitHub: https://github.com/PolinaLinaNechaeva  
🔗 LinkedIn: https://www.linkedin.com/in/polina-nechaeva-b3a67a349?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app

---

## 📜 License

MIT License.
