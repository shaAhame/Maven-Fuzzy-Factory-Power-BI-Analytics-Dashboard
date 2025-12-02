
---

# 📊 Maven Fuzzy Factory — Power BI Analytics Dashboard

### **Marketing & Revenue Performance Insights for E-Commerce**

This repository contains a complete **Power BI analytics solution** built on the **Maven Fuzzy Factory** e-commerce dataset.
The project includes **two fully interactive dashboards** that provide deep insights into marketing performance, user behavior, and revenue trends.

---

## 📁 Repository Contents

| File / Link                         | Description                                                                                                                                                                                                                                 |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🔗 Power BI Dashboard (PBIX)**    | *(Hosted on Google Drive due to large file size)*  <br> 👉 [https://drive.google.com/file/d/1dfVPcQUIR51ma_MM_z4lEvc_PxRnOf5r/view?usp=sharing](https://drive.google.com/file/d/1dfVPcQUIR51ma_MM_z4lEvc_PxRnOf5r/view?usp=sharing)         |
| **📦 Dataset (ZIP)**                | 👉 [https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/Maven%2BFuzzy%2BFactory.zip](https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/Maven%2BFuzzy%2BFactory.zip) |
| **🖼 Dashboard Page 1 (Marketing)** | 👉 [https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_1.png](https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_1.png)                                   |
| **🖼 Dashboard Page 2 (Revenue)**   | 👉 [https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_2.png](https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_2.png)                                   |
| **📄 README.md**                    | Full project documentation                                                                                                                                                                                                                  |

---

# 🚀 Project Overview

The objective of this project is to help an e-commerce business understand:

* Which marketing campaigns drive the most sessions
* How device types and channels influence customer behavior
* Revenue distribution across campaigns and product categories
* Funnel performance from sessions → conversions → orders
* Yearly behavior of traffic and revenue flows

This analytical solution combines **Power Query**, **Data Modeling**, and **advanced DAX measures**.

---

# 📌 Dashboard 1 — Marketing Performance Dashboard

### **KPIs**

* **Total Sessions**
* **Bounce Rate**
* **Conversion Rate**
* **Bounce Sessions**
* **Conversion Sessions**
* **Distinct UTM Sources**

### **Visuals**

* **Funnel:** Sessions → UTM Campaign → UTM Content
* **Line Chart:** Yearly session trends
* **Table:** UTM Source vs Total Sessions *(with conditional formatting)*
* **Bar Chart:** Device Type vs Sessions
* **Slicers:**

  * Year
  * UTM Content
  * UTM Campaign

### **Insights**

* Identify campaign effectiveness
* Detect high-bounce sources
* Compare mobile vs desktop traffic
* Determine which content drives engagement

---

# 📌 Dashboard 2 — Sales & Revenue Dashboard

### **KPIs**

* **Total Orders**
* **Total Revenue**
* **Average Revenue per Order (AOV)**
* **Conversion Sessions → Orders**

### **Visuals**

* **Funnel:** Revenue by UTM Campaign → UTM Content
* **Line Chart:** Yearly Revenue Trend
* **Bar Chart:** Revenue by Product Category
* **Table:** UTM Source vs Total Revenue *(conditional formatting)*
* **Slicers:**

  * Year
  * UTM Content
  * UTM Campaign

### **Insights**

* Campaigns generating the highest revenue
* High-value product categories
* Performance shifts across years
* Full conversion funnel effectiveness

---

# 🧮 Key DAX Measures

* `Total Sessions`
* `Bounce Sessions`
* `Bounce Rate`
* `Conversion Sessions`
* `Conversion Rate`
* `Distinct UTM Sources`
* `Number of Orders`
* `Total Revenue`
* `Average Order Value (AOV)`

These measures are essential for evaluating marketing performance and revenue metrics.

---

# 🧱 Data Model

The data model uses a **star schema** with fact and dimension tables:

### **Fact Tables**

* orders
* order_items
* order_item_refunds
* website_sessions
* website_pageviews

### **Dimension Tables**

* products
* users
* date

Relationships were built using foreign keys to ensure clean and accurate cross-table aggregations.

---

# 📚 Data Dictionary (Summary)

### **Orders**

* Unique order information
* Includes revenue and COGS

### **Order Items**

* SKU-level breakdown
* Indicates primary vs secondary items

### **Refunds**

* Tracks refund events and amounts

### **Products**

* Product catalog including launch timestamps

### **Website Sessions**

* Tracks session-level marketing attributes (UTM source, campaign, content)
* Device type
* Repeat vs first-time users

### **Website Pageviews**

* Page-level tracking including URLs visited

---

# 🖼 Dashboard Preview

### **Marketing Performance Dashboard**

![Page 1](https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_1.png)

### **Sales & Revenue Dashboard**

![Page 2](https://github.com/shaAhame/Maven-Fuzzy-Factory-Power-BI-Analytics-Dashboard/blob/main/page_2.png)

---

# 🛠 Tools Used

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Relational Data Modeling**
* **Maven Fuzzy Factory Dataset**

---

# 📥 How to Use

1. Download the **PBIX dashboard** from Google Drive.
2. Download and unzip the **dataset**.
3. Open `Maven Fuzzy Factory.pbix` in **Power BI Desktop**.
4. Load the dataset into the model.
5. Refresh and explore the visual insights.

---

👤 **Contact / Credits**

**Shakeeb Ahamed**  
**B.Sc (Hons) Financial Mathematics and Industrial Statistics – University of Ruhuna, Sri Lanka**  
**Advanced Diploma in Data Science – NIBM, Sri Lanka**  
**GitHub:** https://github.com/shaAhame  

---

**If you want, I can also add:**  
  
⭐ **Table of Contents**  
⭐ **Project Roadmap Section**    
⭐ **Custom Banner Image**  

Just say **“add enhancements”** and I will upgrade it fully.

