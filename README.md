# Mobile Sales Data Analysis with Power BI

This project is a comprehensive analysis and visualization of mobile sales data using Excel and Power BI. The dataset provides valuable insights into sales trends, customer behavior, and regional performance. The workflow demonstrates advanced data modeling, DAX calculations, and dashboard creation.

## Dataset Overview

The dataset is derived from the `Mobile Sales Data.xlsx` file and contains the following key details:

### Sheet: `Sales Data`

| Column Name        | Description                                     |
|--------------------|-------------------------------------------------|
| **Order ID**       | Unique identifier for each sales transaction.  |
| **Order Date**     | Date of the order.                             |
| **Product**        | Name of the mobile product sold.               |
| **Category**       | Product category (e.g., Smartphone, Accessory).|
| **Sales Amount**   | Revenue generated from the transaction.        |
| **Units Sold**     | Number of units sold in the transaction.       |
| **Region**         | Geographical region where the sale occurred.   |
| **Customer Segment** | Customer type (e.g., Retail, Wholesale).     |
| **Profit**         | Profit margin for the transaction.             |

The dataset is cleaned and prepared for advanced analysis using PowerQuery.

---

## Project Workflow

### 1. Understanding the Data (Excel & PowerQuery)
- Explored the dataset to understand its structure, quality, and trends.
- Cleaned and transformed the data using PowerQuery in Power BI, ensuring it was free of duplicates, errors, and inconsistencies.

### 2. Creating a Custom Calendar (Power BI)
- Built a **Custom Calendar Table** to enable advanced time-based analysis.
- Added fields such as:
  - Year, Quarter, Month, Week, and Day
  - Month Name and Weekday Name for improved readability

### 3. Building Relationships (Data Model Tab in Power BI)
- Established relationships between the **Sales Data** table and the **Calendar Table**.
- Configured one-to-many relationships to ensure seamless integration and accurate computations.

### 4. Performing Required DAX Calculations
- Implemented essential DAX measures to calculate metrics like:
  - **Total Sales**: Sum of sales amounts.
  - **Average Sales**: Average revenue per transaction.
  - **Profit Margin**: Profit as a percentage of sales.

### 5. Calculating MTD, QTD, and YTD Metrics
- Used DAX to compute:
  - **MTD (Month-to-Date)**: Sales from the start of the current month.
  - **QTD (Quarter-to-Date)**: Sales from the start of the current quarter.
  - **YTD (Year-to-Date)**: Sales from the start of the current year.

### 6. Analyzing Same Period Last Year (SPLY)
- Developed DAX measures to compare metrics with the same period in the previous year.
- Examples include:
  - **Sales (SPLY)**
  - **Profit (SPLY)**

---

## Project Deliverables

### Power BI Dashboard
A visually appealing and interactive dashboard was created to showcase key insights. The dashboard includes:
1. **Sales Performance Trends**: Visualizations for MTD, QTD, and YTD comparisons.
2. **Year-over-Year Analysis**: Performance compared to the same period last year.
3. **Profitability Insights**: Region-wise and product-wise profit trends.
4. **Customer Behavior Analysis**: Insights based on customer segments.

---

## Tools & Technologies Used

- **Microsoft Excel**: Initial data exploration and preparation.
- **Power BI**: Data modeling, visualization, and dashboard creation.
- **DAX (Data Analysis Expressions)**: Advanced calculations for metrics and trends.

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/<Your-GitHub-Username>/<Repository-Name>.git
2. Open the .pbix file in Power BI Desktop.
3. Review and customize the dashboard to suit your analysis needs.

---

## Key Learnings
1. Data Cleaning: How to clean and transform raw data using PowerQuery.
2. Custom Calendar Creation: Designing a calendar table for time intelligence.
3. Data Modeling: Establishing relationships between tables in Power BI.
4. DAX Calculations: Writing measures for advanced analytics like MTD, QTD, YTD, and SPLY.
5. Dashboard Design: Crafting insightful and user-friendly visualizations.

---

## About
This project was undertaken by Subham Jena, a final-year B.Tech student passionate about data analytics. For more information, visit my LinkedIn Profile or check out my other projects.

---

This script includes all the details you provided and follows a clear structure to ensure usability. If you'd like to tweak any sections or add screenshots/links, let me know!
