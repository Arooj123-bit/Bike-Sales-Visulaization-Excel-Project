# 🚴 Bike Sales Visualization Project

## 📜 Project Overview

This project is a detailed **Data Visualization and Analysis exercise** using a large bike sales dataset. The primary goal was to practice data manipulation and aggregation techniques, including **filtering** and **sorting**, followed by creating compelling visualizations.

The project demonstrates proficiency in:
1.  **Data Preparation:** Cleaning, filtering, sorting, and aggregating raw data in Excel.
2.  **Visualization:** Creating **Line Charts**, **Bar Charts**, and **Pie Charts** to analyze key business metrics (revenue, profit, sales distribution).

## 💾 Data Source

The analysis is based on a comprehensive bike sales dataset, which includes transactional details for various bike products, accessories, and clothing across multiple global regions. The original data is contained in the sheet/file: `Bike_Sales_Visualizations_Lab - Copy arooj.xlsx - Sales Data.csv`.

---

## ⚙️ Data Preparation and Manipulation

Before creating the final charts, several data preparation steps were performed on the raw sales data to isolate and structure the information needed for each visualization.

### Filtering and Sorting Techniques Used:

| Technique | Purpose | Example Application |
| :--- | :--- | :--- |
| **Filtering** | To isolate specific subsets of data for focused analysis. | Filtering the main sales data to only include transactions for a specific **Year** or **Product Category** (e.g., *Bikes*), or a specific **Country**. |
| **Sorting** | To arrange data in a meaningful order, often before creating a chart, to emphasize rankings or trends. | Sorting the aggregated revenue data **from largest to smallest** by Country (e.g., for the Bar Chart) to quickly identify the top performers. |
| **Pivot Tables** | Used extensively to summarize, count, and aggregate the filtered/sorted data (e.g., summing Revenue by Country and Product Category). |

---

## 📊 Visualizations and Analysis

The project includes three main types of visualizations, each designed to answer specific business questions.

### 1. Line Chart: Annual Revenue and Profit Trend

**Question:** How have the company's annual profit and revenue changed over time?

* **Data Used:** Annual Revenue and Profit from **2017 to 2021**.
* **Visualization Focus:** A **Line Chart** to clearly display the trend and growth rate of both metrics simultaneously.
* **Key Finding:** There is a consistent and strong **upward trend** in both Annual Revenue and Annual Profit, indicating healthy business growth year-over-year.
* <img width="1256" height="442" alt="Screenshot 2025-11-18 120339" src="https://github.com/user-attachments/assets/658853e4-ee2b-4520-ae2f-4125fb6e55bb" />


### 2. Bar Chart: Product Revenue by Country

**Question:** What are the top-performing product categories and countries in terms of revenue?

* **Data Used:** Revenue aggregated by **Country** and **Product Category** (Bikes, Accessories, Clothing).
* **Preparation Note:** The summary data was **sorted** by *Grand Total Revenue* in descending order to visually prioritize the most successful countries.
* **Visualization Focus:** A **Clustered Bar Chart** to compare revenue contributions side-by-side across regions and product types.
* **Key Finding:** **Bikes** is the dominant revenue driver globally. The **United States** and **Australia** are the top-performing countries by total revenue.
* <img width="1436" height="444" alt="Screenshot 2025-11-18 120414" src="https://github.com/user-attachments/assets/e44d1c13-c302-4356-9e3c-b80e28f1a469" />


### 3. Pie Chart: Revenue Distribution by Age Group

**Question:** Which age groups contribute the most to the total revenue?

* **Data Used:** Total revenue distributed among the four primary **Age Groups**: Adults (35-64), Young Adults (25-34), Youth (<25), and Seniors (64+).
* **Visualization Focus:** A **Pie Chart** to illustrate the proportion of total revenue contributed by each segment.
* **Key Finding:** The largest share of the total revenue comes from the **Adults (35-64)** and **Young Adults (25-34)** groups, highlighting the importance of targeting customers in these demographics.
* <img width="1023" height="390" alt="Screenshot 2025-11-18 120514" src="https://github.com/user-attachments/assets/8cee65cb-e748-4eaf-964f-20b39e79fa72" />


---

## 🛠️ Technology Used

* **Microsoft Excel:** Data preparation (filtering, sorting, aggregation with Pivot Tables), and visualization creation.
* **Markdown:** For documenting the project and creating this `README.md` file.
