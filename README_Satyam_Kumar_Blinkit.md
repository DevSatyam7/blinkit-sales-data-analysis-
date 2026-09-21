# Blinkit Sales & Customer Analysis

## IBM SkillsBuild Data Analytics with AI Internship 2026

**Student:** Satyam Kumar

---

## Project Overview

This project analyzes a **synthetic Blinkit-style quick-commerce sales dataset** to identify patterns in sales revenue, profit, product categories, city performance, customer ratings, delivery time, payment methods, customer types, and monthly sales trends.

The project follows an end-to-end data analytics workflow from dataset loading and cleaning through exploratory analysis, KPI calculations, grouping, visualization, insights, and business observations.

> **Disclaimer:** The dataset is synthetic and created for educational/data-analytics purposes. It is not official or proprietary Blinkit company data.

---

## Problem Statement

Quick-commerce businesses generate large amounts of order and customer data. Analyzing this information can help identify patterns in revenue, profitability, product-category performance, city-level performance, customer behavior, delivery time, and sales trends.

This project demonstrates how Python-based data analytics can be used to clean and analyze sales data, answer practical business questions, visualize findings, and communicate analytical insights.

---

## Dataset

The project uses an educational synthetic dataset containing **1,800 order-level records** and **15 columns**.

| Attribute | Value |
|---|---:|
| File | `blinkit_sales_dataset_educational.csv` |
| Records | 1,800 |
| Columns | 15 |
| Data Type | Synthetic educational quick-commerce sales data |

### Dataset Columns

`Order_ID`, `Order_Date`, `City`, `Category`, `Product`, `Quantity`, `Unit_Price`, `Discount_Pct`, `Sales`, `Cost`, `Profit`, `Customer_Rating`, `Delivery_Minutes`, `Payment_Method`, `Customer_Type`

### Categories

- Fruits & Vegetables
- Dairy & Breakfast
- Snacks
- Beverages
- Household
- Personal Care

### Cities

Patna, Delhi, Bengaluru, Mumbai, Hyderabad, Pune, Kolkata, Jaipur

---

## Project Structure

```text
Blinkit-Sales-Data-Analysis/
│
├── Satyam_Kumar_Blinkit_Sales_Analysis.ipynb
├── Satyam_Kumar_Blinkit_Sales_Analysis_requirements.txt
├── Satyam_Kumar_Blinkit_Sales_Analysis_Project_Report.docx
├── blinkit_sales_dataset_educational.csv
├── README.md
│
└── analysis_output/
    ├── kpis.csv
    ├── category_summary.csv
    ├── city_summary.csv
    ├── monthly_trend.csv
    ├── revenue_by_category.png
    ├── revenue_by_city.png
    └── monthly_revenue.png
```

---

## Notebook Sections

1. Project Overview
2. Problem Statement
3. Dataset Information
4. Import Libraries
5. Load Dataset
6. Data Understanding
7. Data Cleaning
8. Exploratory Data Analysis
9. KPI Calculations
10. Category-wise Analysis
11. City-wise Analysis
12. Monthly Sales Trend
13. Customer Analysis
14. Delivery Performance
15. Data Visualizations
16. Key Insights
17. Business Observations
18. Conclusion

---

## Key Findings

The following findings were calculated from the synthetic dataset:

| KPI / Finding | Result |
|---|---:|
| Total Orders | 1,800 |
| Total Revenue | ₹465,691.66 |
| Total Profit | ₹131,456.51 |
| Total Quantity Sold | 3,242 |
| Average Order Value | ₹258.72 |
| Average Customer Rating | 4.10 / 5 |
| Average Delivery Time | 15.77 minutes |
| Highest Revenue Category | Personal Care |
| Highest Revenue City | Patna |
| Highest Revenue Month | April 2026 |

These findings describe patterns in the synthetic dataset and should not be interpreted as actual Blinkit business statistics.

---

## Category Analysis

The category-level analysis compares order volume, revenue, and profit across product categories.

In this synthetic dataset, **Personal Care** generated the highest revenue, followed by **Household**.

Results are exported to:

`analysis_output/category_summary.csv`

---

## City Analysis

The city-level analysis compares sales and profitability across the eight cities represented in the dataset.

In this synthetic dataset, **Patna** recorded the highest revenue, followed by **Bengaluru** and **Delhi**.

Results are exported to:

`analysis_output/city_summary.csv`

---

## Monthly Sales Analysis

The dataset covers **January 2026 to August 2026**. Monthly revenue was analyzed to identify changes in sales performance.

The highest monthly revenue in this dataset occurred in **April 2026**.

Results are exported to:

`analysis_output/monthly_trend.csv`

---

## Customer Analysis

The project examines:

- Customer type
- Customer rating
- Payment method
- Order quantity
- Sales value
- Delivery time

These variables are used to understand basic customer and order patterns within the synthetic dataset.

---

## Delivery Performance

Delivery time is analyzed using the `Delivery_Minutes` field.

The dataset has an average delivery time of approximately **15.77 minutes**.

This is an educational operational metric and is not a real-world Blinkit service-level measurement.

---

## Data Visualizations

The project generates:

- Revenue by Category
- Revenue by City
- Monthly Revenue Trend

Generated charts are stored in:

`analysis_output/`

---

## Business Observations

### Revenue Monitoring
Tracking revenue across categories and cities can demonstrate which areas contribute more strongly to overall sales.

### Profit Analysis
Comparing sales with cost and profit helps evaluate financial performance across categories and locations.

### Category Planning
Category-level performance can support exploratory analysis of inventory, promotions, and product assortment.

### City Performance
City-level analysis demonstrates how regional sales performance can be compared using consistent data.

### Customer Experience
Customer ratings and delivery times can be analyzed alongside sales performance.

> These are observations from synthetic educational data, not recommendations based on Blinkit's actual internal operations.

---

## Technologies Used

| Technology / Library | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data loading, cleaning, grouping and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive analysis |
| OpenPyXL | Spreadsheet-related support |

---

## How to Run

### 1. Clone or Download the Repository

```bash
git clone <repository-url>
cd blinkit-sales-data-analysis
```

### 2. Install Dependencies

```bash
pip install -r Satyam_Kumar_Blinkit_Sales_Analysis_requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook Satyam_Kumar_Blinkit_Sales_Analysis.ipynb
```

### 4. Run All Cells

Open the notebook and run the cells from top to bottom.

---

## Deliverables

| File | Description |
|---|---|
| `Satyam_Kumar_Blinkit_Sales_Analysis.ipynb` | Main data analysis notebook |
| `Satyam_Kumar_Blinkit_Sales_Analysis_Project_Report.docx` | Project report |
| `Satyam_Kumar_Blinkit_Sales_Analysis_requirements.txt` | Python dependencies |
| `README.md` | Project documentation |
| `blinkit_sales_dataset_educational.csv` | Synthetic educational dataset |

---

## Dataset Disclosure

This project intentionally uses a **synthetic educational dataset**. It demonstrates data cleaning, exploratory analysis, aggregation, KPI calculation, visualization, and business insight generation.

The dataset is **not official Blinkit data**, and the results must not be presented as actual Blinkit company statistics.

---

## Limitations

- The dataset is synthetic.
- It does not represent actual Blinkit customers or transactions.
- It covers a limited number of cities and product categories.
- Results are intended for educational analytics.
- No real company-level operational or financial conclusions can be drawn.
- The analysis does not use proprietary Blinkit information.

---

## Future Scope

- Interactive dashboards using Power BI or Tableau
- Customer segmentation
- Advanced sales forecasting
- Product-level demand analysis
- Delivery-time trend analysis
- Cohort and retention analysis
- Promotion and discount effectiveness analysis
- Advanced machine-learning models
- Interactive business dashboards

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python and a synthetic quick-commerce sales dataset.

The analysis covers revenue, profit, category performance, city performance, customer behavior, delivery time, and monthly sales trends. It demonstrates how structured data analysis and visualization can convert raw order data into understandable business insights.

The project is prepared as an educational submission for the **IBM SkillsBuild Data Analytics with AI Internship 2026**.

---

**IBM SkillsBuild Data Analytics with AI Internship 2026**  
**Student: Satyam Kumar**
