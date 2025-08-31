# 🍕 Pizza Sales Dashboard  

## 📌 Project Title / Headline  
🔥 **Pizza Analytics: Sales & Performance Dashboard**  
A dynamic, interactive Power BI dashboard designed to analyze pizza sales performance — focusing on revenue, order patterns, best/worst pizzas, and customer behavior insights.  

---

## 📝 Short Description / Purpose  
The **Pizza Sales Dashboard** is an analytical **Power BI report** that provides a comprehensive overview of sales trends. It highlights **total revenue, total orders, average order value (AOV), top-performing pizzas, and sales distribution by time of day, category, and size**.  

This tool is intended for **restaurant managers, business analysts, and data enthusiasts** to track performance, optimize menu offerings, and improve customer satisfaction.  

---

## ⚙️ Tech Stack  
The dashboard was built using the following tools and technologies:  

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation.  
- 📂 **Power Query** – Data transformation and cleaning layer.  
- 🧠 **DAX (Data Analysis Expressions)** – For calculated measures, KPIs, and rankings.  
- 📝 **Data Modeling** – Relationships among tables (`orders`, `order_details`, `pizzas`, `pizza_type`) for cross-filtering and aggregation.  
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.  

---

## 📂 Data Source  
- **Dataset**: Pizza Sales Data (Kaggle / Educational Dataset)  
- **Tables Included**:  
  - `order_details` → order_id, pizza_id, quantity  
  - `orders` → order_id, date, time  
  - `pizzas` → pizza_id, pizza_type_id, size, price  
  - `pizza_type` → pizza_type_id, name, category, ingredients  

---

## 🌟 Features / Highlights  

### 🔹 Business Problem  
Pizza chains generate thousands of orders daily, but managers struggle to quickly identify:  
- Which pizzas are **best/worst sellers**  
- What **time of day** generates the most sales  
- How **pizza sizes** impact revenue  
- Whether a few pizzas contribute to the **majority of revenue (Pareto 80/20 rule)**  

### 🔹 Goal of the Dashboard  
To deliver an **interactive visual tool** that:  
- Tracks overall sales performance (Revenue, Orders, AOV)  
- Identifies **top-performing pizzas & categories**  
- Provides **time-based insights** (morning, afternoon, evening, night sales)  
- Supports **menu optimization & marketing decisions**  

### 🔹 Walkthrough of Key Visuals  
- **Executive KPIs (Top Section)**  
  - Total Revenue  
  - Total Orders  
  - Average Order Value (AOV)  
  - Best Pizza (by revenue)  
  - Worst Pizza (by revenue)  

- **Revenue by Pizza Category (Bar Chart)**  
  Compare revenue across categories (Veggie, Chicken, Supreme, Classic).  

- **Orders by Time of Day (Donut Chart)**  
  Distribution of orders across **Morning, Afternoon, Evening, Night**.  

- **Revenue by Pizza Size (Column Chart)**  
  Shows contribution of different sizes (S, M, L, XL, XXL).  

- **Pareto Analysis (Cumulative Revenue %)**  
  Identifies how the **top-selling pizzas contribute to total revenue**.  

---

## 📸 Screenshots / Demos  

### Dashboard Preview  
![Pizza Sales Dashboard](https://github.com/krishnakumbhaj/Pizza_Sales_Dashboard/blob/main/Pizza_Sales_Dashboard.png)
*(Replace the path above with your actual image URL or keep the image in `/images` folder of your repo.)*  

---

## 🚀 Business Impact & Insights  
- **Menu Optimization** → Identify pizzas driving 80% of revenue and focus promotions accordingly.  
- **Operational Efficiency** → Allocate resources based on peak order times.  
- **Customer Insights** → Understand customer preferences by category & size.  
- **Revenue Growth** → Improve strategy by focusing on high-performing products.  

---

## 🙌 Author  
👤 **Krishna Sharma**  
- 📧 Reach me on [LinkedIn](https://linkedin.com/in/your-profile)  
- 🌐 Portfolio: *(add if you have one)*  
