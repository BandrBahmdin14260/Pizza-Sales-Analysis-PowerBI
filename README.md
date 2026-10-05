# 🍕 Pizza Sales Performance Dashboard

## 📌 Overview
This repository features an interactive **Power BI Dashboard** built to analyze pizza restaurant sales, order trends, and category performance. The goal of this project is to transform raw transactional data into actionable operational insights for business decision-making.

---

## 📸 Dashboard Preview
![Dashboard Preview](SharedScreenshot.jpg)

---

## 🏗️ Data Model & Relationships
The dataset comprises 4 relational tables structured and modeled in Power BI using a Star Schema / Relational layout:
- `orders`: Contains order dates and timestamps.
- `order_details`: Tracks individual line items and quantities sold per order.
- `pizzas`: Holds pricing details and size configurations.
- `pizza_types`: Contains pizza categories, names, and ingredients.

![Data Model & ERD](RealationData.jpg)

---

## 🧹 Data Cleaning & Preparation
Data cleaning and ETL operations were executed within **Power Query**:
- Verified 100% column quality across all entities (zero errors or missing values).
- Structured relationships with primary/foreign keys (1-to-Many).
- Calculated key metrics and top-performing item filters.

![Data Quality & Power Query](SharedScreenshotData.jpg)

---

## 📊 Key Insights & Metrics
- **Total Revenue:** $1,578.30
- **Total Quantity Sold:** 49,574 units
- **Top Sales Category:** Classic (30.03% of volume)
- **Peak Month:** July (4,392 units sold)
- **Best-Selling Product:** The Classic Deluxe Pizza

---

## 🛠️ Tools & Technologies
- **Power BI Desktop**
- **Power Query (ETL & Data Prep)**
- **Data Modeling (Relational Design)**
- **DAX & Interactive Visualizations**
