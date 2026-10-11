# Food Delivery Analytics Dashboard | Power BI

## Dashboard Preview

![Food Delivery Dashboard Preview](<Dashboard Preview.png>)

## Project Overview

This project is a Food Delivery Analytics Dashboard built using Microsoft Power BI.

The main goal of this project is to organize food delivery sales data and present it through an interactive dashboard. I used four monthly sales files and an Excel file containing three dimension tables to build the data model.

## Tools Used

- **Microsoft Power BI** – Dashboard creation and data visualization
- **Power Query** – Data cleaning, transformation, and appending monthly sales data
- **DAX** – Creating calculations and measures
- **Microsoft Excel** – Storing sales data and dimension tables

## Project Files

| File Name | Description |
|---|---|
| `April sales.xlsm` | April monthly sales data |
| `February sales.xlsm` | February monthly sales data |
| `January sales.xlsm` | January monthly sales data |
| `March sales.xlsm` | March monthly sales data |
| `Food, Customer, Restaurant Details data.xlsx` | Contains three dimension tables: Food, Customer, and Restaurant Details |
| `Food Delivery App Dashboard.pbix` | Power BI dashboard and data model |
| `Dashboard Preview.png` | Dashboard screenshot for preview |

## Data Preparation

I used Power Query to prepare the data for analysis.

1. Imported the four monthly sales files into Power BI.
2. Appended the monthly sales data into one fact table.
3. Used the Excel file containing the Food, Customer, and Restaurant Details dimension tables.
4. Created relationships between the fact table and the dimension tables to build the data model.

## Data Model

The project uses a fact table and three dimension tables.

- **Fact Table:** Contains the combined sales data from January, February, March, and April.
- **Food Dimension:** Contains food-related details.
- **Customer Dimension:** Contains customer-related details.
- **Restaurant Dimension:** Contains restaurant-related details.

These tables are connected through relationships in Power BI to support data analysis.

## Key Learning Outcomes

Through this project, I gained practical experience in:

- Combining data from multiple Excel files using Power Query.
- Appending monthly sales data into a single fact table.
- Working with fact and dimension tables.
- Creating relationships between tables in Power BI.
- Building an interactive dashboard to present business data.

## Power BI File

You can find the Power BI dashboard file in this repository:

`Food Delivery App Dashboard.pbix`

Download the file and open it using Microsoft Power BI Desktop to explore the report.

---

**Feedback is welcome!** I am continuously learning and building projects to improve my data analytics skills.

