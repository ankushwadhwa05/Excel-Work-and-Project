# Bike Sales Analysis & Dashboard

###  Project Overview
This project analyzes a dataset of bike buyers to identify trends in customer demographics and purchasing behavior. The goal was to clean raw data and build an interactive dashboard to help stakeholders understand **who** buys bikes and **why**.

![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

---

###  Dashboard Preview

[<img width="502" height="200" alt="Screenshot 2026-02-10 191835" src="https://github.com/user-attachments/assets/661059aa-1265-4b35-9b81-8bd9954dbe2c" />](https://raw.githubusercontent.com/ankushwadhwa05/Excel-Work-and-Project/c45ec28def17511c3bd0a2336f0c07ccf6cae8ac/Screenshot%202026-02-10%20191835.png)


---

###  Process & Workflow

**1. Data Cleaning**
Before analysis, the raw dataset required significant cleaning to ensure accuracy:
* **Removed Duplicates:** Eliminated duplicate records to prevent skewed results.
* **Standardization:** Found and replaced abbreviations (e.g., changing "M" to "Married", "S" to "Single") to make the data more readable for filtering.
* **Formatting:** Converted currency and income columns to the correct numeric formats.
* **Age Grouping:** Created custom age brackets (Adolescent, Middle Age, Old) using nested `IF` statements to categorize customers better.

**2. Data Analysis (Pivot Tables)**
I created several pivot tables to uncover relationships between variables:
* Average Income vs. Bike Purchase (by Gender).
* Customer Commute Distance vs. Bike Purchase likelihood.
* Customer Age Brackets vs. Sales.

**3. Visualization**
* Built a dynamic dashboard with **Slicers** (Marital Status, Region, Education) to allow users to filter the data interactively.

---

###  Key Insights
* **Income Impact:** Customers with higher average incomes were more likely to purchase a bike.
* **Commute Distance:** People with shorter commute distances (0-1 Miles) bought more bikes than those with long commutes.
* **Age Demographics:** Middle-aged customers accounted for the highest volume of sales.
