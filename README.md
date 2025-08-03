# 📊 Hemtech Enterprise Sales & Marketing Performance Report

## 🏢 Project Overview

**Hemtech Enterprise** is one of the leading distributors of home appliances and gadgets in Nigeria, with an annual revenue of over **$2 million**.

To boost regional sales, Hemtech launched a focused **marketing campaign** across **four key cities**:
- Abuja
- Lagos
- Delta
- Enugu

This project analyzes sales and marketing data over a 3-month period using **Power BI**, providing insights into campaign performance, regional sales dynamics, and marketing return on investment (ROI).

---

## 🎯 Objective

The primary goal of this project was to develop a Power BI dashboard and report to answer the following **key performance questions**:

- 💰 What are the **total sales** and **average sales**?
- 🌍 What are the **total sales across regions**?
- 🛒 What is the **total number of orders** placed?
- 📉 What is the **total and monthly marketing expenditure**?
- 📈 How have **sales changed over time**, and how do they correlate with marketing spending?
- 🥇 Which **region performed best**, and how did rankings evolve?

---

## 📁 Data Source

- Format: Microsoft Excel (.xlsx)
- Source: Internal sales and marketing data from 4 target cities
- Fields included: `Date`, `Region`, `Sales`, `Orders`, `Marketing Spend`, etc.

---

## 🧹 Data Cleaning & Transformation

- Imported the dataset into **Power BI**
- Cleaned and formatted data using **Power Query Editor**
- Verified column names, corrected date types, and ensured numeric fields were accurate

---

## 📊 Visualizations

Created an interactive **Power BI dashboard** using the following visuals:

| Visual Type        | Description |
|--------------------|-------------|
| **Card Visuals**   | Display total sales, average sales, order count, and marketing spend |
| **Multi-Row Cards**| Show monthly breakdown of sales and marketing spend |
| **Waterfall Chart**| Illustrate how monthly marketing spend accumulates to total spend |
| **Ribbon Chart**   | Visualize sales performance rankings across regions over time |

---

## 📈 Key Insights

- **Total Sales**: ~$1.04 million  
- **Average Monthly Sale per Order**: ~$64.75K  
- **Total Orders**: 16  
- **Total Marketing Spend**: ~$126K  

- **East and South (Team B)** significantly outperformed North and West (Team A)
- **Marketing ROI** was higher for Team B; e.g., in July:
  - $17K extra spend led to $223K sales (Team B)
  - $20K extra spend led to $65K sales (Team A)
- **East Region** maintained the highest sales rank throughout the campaign
- **West Region's** marketing spend did not yield proportionate sales, suggesting inefficiencies

---

## ✅ Conclusion

This Power BI project provides **actionable insights** into Hemtech’s sales performance, regional contributions, and marketing efficiency. It demonstrates how data visualization can guide strategic decisions, improve resource allocation, and track the impact of business campaigns.

---

## 🛠 Tools Used

- Microsoft Excel  
- Microsoft Power BI  
- Power Query  
- DAX (for KPI calculations)

---

## 📷 Screenshots

> *(Include screenshots of your Power BI dashboard here if applicable)*  
> Example:
> ![Dashboard Overview](images/dashboard-overview.png)

---

## 📂 Project Structure

```bash
Hemtech-Sales-Report/
│
├── data/
│   └── Hemtech_Marketing_Campaign.xlsx
│
├── visuals/
│   └── dashboard-overview.png
│
├── Hemtech_Sales_Analysis.pbix
├── README.md
