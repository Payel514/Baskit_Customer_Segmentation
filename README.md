# 🛒 Payel_Baskit_Customer_Segmentation

This repository contains a comprehensive Excel-based business analytics project for **Baskit**, a premium delivery service based in Bangalore. The project includes full-scale data cleaning, item-level analysis, RFM-based customer segmentation, feedback diagnostics, and dynamic dashboards — all implemented using Microsoft Excel with advanced formula logic and automation features.

---

## 📌 Project Objective

To help **Baskit** gain deeper insights into their top customers, delivery performance, and cancellation trends using historical order data. This includes:

- Analyzing order-level data for item performance
- Identifying high-cancellation dark stores
- Segmenting customers using RFM analysis
- Generating dynamic dashboards & personalized feedback reports
- Sending tailored messages to at-risk customers

---

## 🗂️ Project Structure

| **Sheet Name**           | **Description** |
|--------------------------|------------------|
| `Data`                   | Raw order transaction records in semi-structured format |
| `Data Cleaning`          | Structured tabular format prepared using data extraction and transformation |
| `Order_data`             | Line-level item extraction with categories, prices, and calculated order totals |
| `Sales Dashboard`        | Interactive dashboard visualizing sales metrics |
| `Cancellation Report`    | Insights on cancellation trends, feedback issues, and dark store performance |
| `Segment Table`          | Lookup mapping of RFM scores to customer segment names |
| `RFM Segmentation`       | Customer-wise Recency, Frequency, Monetary value computation |
| `RFM Score Calculation`  | Mean, deviation, and score scales for Recency, Frequency, and Monetary value |
| `Top Customer Analysis`  | Dynamic analysis of delivery status and feedback for top customer groups |
| `Message`                | Pre-defined message template for specific customer complaints |
| `Customized Message`     | Automated message report for customers with consecutive or last-order cancellations |

---

## 📊 Key Features & Tasks

### ✅ **Data Cleaning**
- Parsed complex semi-structured text (with '//' and '+' delimiters)
- Extracted fields like customer name, location, item names, date, payment mode, and feedback

### ✅ **Order-Level Analysis**
- Identified individual items in orders using string logic
- Assigned categories and prices
- Calculated `Item Total` per order for analytics

### ✅ **Sales Dashboard**
- Built an interactive dashboard visualizing:
  - Top-selling items
  - Item categories performance
  - Payment mode analysis
  - Order trends over time

### ✅ **Cancellation Report**
- **Dark Store-wise** cancellation rate with conditional formatting
- **Dynamic Feedback Analysis** with dropdown-based store selection
- Highlighted most common cancellation causes (e.g., *Delayed Delivery, Item not available*)

### ✅ **RFM Segmentation (As of 1st Jan 2024)**
- Calculated:
  - **Recency** (Days since last order)
  - **Frequency** (Total orders)
  - **Monetary** (Total spend)
- Scaled each customer using RFM score ranges based on company policy
- Segmented into:
  - **Top-tier Customers**
  - **Loyal Customers**
  - **Potential Loyal Customers**

### ✅ **Top Customer Delivery & Feedback Dashboard**
- Delivery report with **last 5 orders** per customer
- Highlighted **Cancelled Orders** in red, **Delivered** in green
- Tag for **Consecutive Cancellations**
- Feedback report showing:
  - Top complaints
  - Major issue per customer
  - Count of each feedback

### ✅ **Customized Messaging**
- Generated automatic, **issue-based personalized messages**
- Mapped major customer complaints (e.g., *Delayed Delivery*) to predefined messages
- Targeted customers with:
  - Last order cancelled
  - Consecutive cancellations

---

## 🧠 Tools & Concepts Used

- Microsoft Excel (Functions, Dropdown, PivotTables, Named Ranges, Conditional Formatting)
- RFM Analysis (Recency, Frequency, Monetary scoring)
- Dynamic Dashboards
- Data Cleaning & Text Parsing
- Feedback Classification
- Lookup & Automation Logic
- Customer Experience Analytics

---

## 📂 File Description

- `Payel_Baskit.xlsx`  
  ➤ The complete project workbook including all data, reports, calculations, and dashboards.

---

## 📬 How to Use

1. Download the `Payel_Baskit.xlsx` file.
2. Open in Microsoft Excel.
3. Navigate through the sheets as per their purpose (see table above).
4. Use dropdown filters in dashboard and analysis sheets for dynamic reporting.
5. All sheets are interconnected; changes in inputs (e.g., customer category) will auto-update the analysis.

---
## 📸 Dashboard Preview

![Dashboard Preview](https://github.com/Payel514/Payel_Baskit_Customer_Segmentation/blob/main/Dashboard_Preview.png)

---
## 📈 Sample Use Cases

- **Business Analysts** looking to implement RFM segmentation using Excel.
- **Customer Success Teams** seeking ways to generate personalized retention strategies.
- **Founders/Startups** who want to measure customer satisfaction using transactional data.
- **Excel Enthusiasts** exploring dynamic dashboards and feedback analysis.

---

## 📬 Contact

**Payel Pramanik**  
📧 payelpramanik444@gmail.com  
🔗 https://www.linkedin.com/in/payel-pramanik-97b083211

---


