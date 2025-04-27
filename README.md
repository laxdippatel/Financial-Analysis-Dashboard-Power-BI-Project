# 📊 Financial Analysis Dashboard | Power BI Project

Welcome to my **Financial Analysis Dashboard** project, built using **Power BI** with financial data spanning from **2019 to 2020**.  
This project showcases the end-to-end process of transforming raw data into meaningful insights through interactive and well-designed visualizations.


![image](https://github.com/user-attachments/assets/c320e7ab-09ad-4995-a6bf-87d380e09674)


---

## ✨ Project Overview

This project demonstrates the creation of a **basic yet powerful financial analysis dashboard**.  
The journey begins by **loading data** from an Excel workbook, followed by **data transformation** using **Power Query Editor**:

- Removed empty columns.
- Adjusted data types (e.g., setting 'Month' and 'Year' as text).
- Applied necessary transformations for a clean dataset.

Since the dataset consisted of only a **single table**, there was no need for setting up any complex data model relationships.

---

## 🧠 DAX Measures Creation

Several **key measures** were created to drive the dashboard's insights:

- **Total Revenue** — `SUM(Revenue Column)`
- **Average Revenue** — `AVERAGE(Revenue Column)`
- **Total Transactions** — `COUNT(First Name Column)`
- **Total Countries** — `COUNT(Country Column)`

All these measures were neatly organized into a dedicated **"Measures Table"** for better management.

---

## 🎨 Report Layout and Design

The report layout was carefully designed to provide a **clean, professional look**:

- Set a **custom background color** using hex codes from an online color palette.
- Inserted and formatted **shapes (rectangles)** to section off areas for slicers and card visuals.
- Designed **card visuals** to display key metrics (Total Revenue, Average Revenue, Total Countries, Total Transactions) with consistent formatting:
  - Custom background and border
  - Shadow effects
  - Bold call-out values
  - Clean black text for better readability

---

## 📈 Visualizations Created

A variety of impactful visualizations were developed:

- **Donut Chart** — Showcasing Total Revenue by Region.
- **Line and Clustered Bar Chart** — Comparing Total Revenue and Average Revenue by Country, with region-based color coding.
- **Tree Map** — Highlighting Total Revenue by Store (Rank).
- **Area Chart** — Illustrating Total Revenue by Quarter.
- **Ribbon Chart** — Depicting Total Revenue by Product and Store (Rank).
- **Matrix Table** — Displaying Sales Representative, Total Transactions, Total Revenue, and Average Revenue with professional formatting.
- **Line and Clustered Column Chart** — Comparing Total Revenue and Average Revenue by Month.

---

## 🛠️ Slicers for Enhanced Interactivity

To make the dashboard dynamic and user-friendly, slicers were added for:

- **Year**
- **Quarter**
- **Store**

All slicers were formatted with the tile option for a visually consistent experience.

---

## 🚀 Conclusion

This project serves as a complete walkthrough of **building a financial analysis report** from **data ingestion to visualization**.  
It reflects best practices in **data transformation**, **measure creation**, **dashboard design**, and **interactivity enhancements** using Power BI.

Thank you for checking out this project! Feel free to ⭐ star this repository if you find it helpful or inspiring.

---
