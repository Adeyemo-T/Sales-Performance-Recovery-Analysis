## Project Background

The company is experiencing a significant downturn, with both **Revenue and Profit falling over 62%** year-over-year. This dramatic decline necessitates an urgent analysis to understand the core drivers and identify immediate opportunities for strategic resource reallocation.

This project thoroughly analyzes transactional data to stabilize the profit decline, capitalize on high-performing segments, and address critical market disparities.

Insights and recommendations are provided on the following key areas:
* **Tracking Revenue Trends:** Evaluation of the monthly sales curve to identify inflection points and recovery signals.
* **Product Line Prioritization:** Analysis of top-performing products to inform inventory and marketing focus.
* **Regional Sales Disparity:** Assessment of sales performance by market to optimize resource allocation.

 **Interactive Dashboard:** The full Power BI Sales Performance dashboard can be accessed [here](https://app.powerbi.com/links/_dOH9dcteQ?ctid=9db3791d-d5d0-4f91-b691-e83929715f73&pbi_source=linkShare).

## Data Structure & Initial Checks
### Data Overview
The analysis was conducted using a single, denormalized **Excel dataset** sourced from the company's historical transaction records. The file contained over **25 variables** related to order details, product information, customer geography, and sales figures.
### Data Cleaning and Preparation
The entire data cleaning and transformation process was executed using **Power Query (M Language)** to ensure data quality and integrity before analysis.

* **Header Promotion:** The first row was promoted to professional column headers (e.g., `ORDERNUMBER`, `PRODUCTLINE`).
* **Data Type Management:** Corrected data types for calculations (e.g., converted currency fields like `SALES` and `MSRP` to decimal/float format).
* **Feature Engineering:** Calculated the essential **Profit** column and the **Year-on-Year Change (YOY)** metrics used across the dashboard.
![Image](https://github.com/user-attachments/assets/88ca3636-2f2e-4855-a85a-3512a236de4d)

## Executive Summary

The company is experiencing a significant downturn, with **Revenue and Profit falling over 62%** year-over-year, alongside a 62.3% drop in total units sold. This decline, while concerning, appears to have bottomed out in April, showing signs of a strong recovery in May. Strategic focus must now shift to capitalizing on the May recovery trend and addressing the critical regional sales disparities.
![Image](https://github.com/user-attachments/assets/08d9cb78-49a6-4514-837d-6debb8d0d1cc)
### Overview of Key Performance Indicators (KPIs)

The overview highlights the critical top-level metrics driving the business narrative, showcasing the severity of the year-over-year decline but also the signs of a recent recovery in the monthly trend.

![Image](https://github.com/user-attachments/assets/5cc62baf-76d0-488e-8f33-bcf81dbf80f8)

### Sales Trend and Market Performance

* **Top Performers:** The top three product lines—**Classic Cars, Vintage Cars, and Motorcycles**—are responsible for the majority of the total sales volume.
* **Regional Disparity:** The **EMEA and NA regions** are the dominant markets, contrasting with critically low sales in the **APAC and Japan regions**.

![Image](https://github.com/user-attachments/assets/dbba27b8-2bde-4eb8-b2ab-8a6f82411bd8)

### Pricing and Customer Deep Dive

* **Pricing Strategy:** The analysis shows that the **Average Price Each** consistently sits **below the Average MSRP**, suggesting a reliance on discounting or volume sales to move products.
* **Key Customers:** A small number of customers, particularly **Euro Shopping Channel**, account for a disproportionately large share of the total sales.
![Image](https://github.com/user-attachments/assets/ef08a30b-f89f-4b97-a9bb-d15d891cfb26)

## Business Recommendations

Based on the uncovered insights, the following actions are recommended to stabilize performance, capitalize on the May recovery, and drive future revenue:

* **Capitalize on the May Recovery:** Immediately investigate the factors that drove the significant revenue spike in May. If the cause is repeatable, **standardize and immediately roll out** that strategy across all regions.
* **Prioritize Top-Performing Inventory:** Focus inventory and marketing efforts almost exclusively on the **Classic Cars and Vintage Cars** product lines, which demonstrate the highest profit potential.
* **Strategic Regional Reallocation:** Reduce investment in the consistently underperforming **APAC and Japan regions**. Reallocate those resources to the dominant and profitable **EMEA and NA regions** to maximize return on investment.
* **Customer Retention Strategy:** Implement proactive retention efforts for the high-volume customers (like **Euro Shopping Channel**) to mitigate risk associated with reliance on key accounts.
* **Review Pricing Strategy:** Investigate the consistent trend of selling below **MSRP**. Determine if current pricing is strategically necessary or if it is unnecessarily eroding profit margins.
