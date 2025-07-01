# Adidas Sales Performance Dashboard: Power BI Project

## Overview and Business Problem

<!-- Placeholder for your main dashboard screenshot or a conceptual diagram -->
<!-- Example: ![Adidas Sales Dashboard Overview](https://github.com/your-username/your-repo/assets/your-image-id/adidas_dashboard_overview.png ) -->
![111](https://github.com/user-attachments/assets/5f34f9af-e15b-4c53-966d-67bc4d5c0daa)


This project focuses on creating a comprehensive Power BI dashboard for Adidas sales data. The goal is to provide a clear, interactive overview of sales performance, identify key trends, and enable data-driven decision-making for various stakeholders, including sales managers, marketing teams, and regional leads. The dashboard addresses the need to quickly understand sales dynamics across different regions, product categories, sales methods, and time periods.

### Key Performance Indicators (KPIs)

-   **Total Sales**: Overall revenue generated.
-   **Units Sold**: Total quantity of products sold.
-   **Operating Margin %**: Profitability percentage from sales.
-   **Sales by Region**: Revenue distribution across geographical areas.
-   **Sales by Product**: Performance of different product categories (e.g., Men's Street Footwear, Women's Apparel).
-   **Sales by Sales Method**: Breakdown of sales via Online, In-store, or Outlet.
-   **Monthly Sales Trend**: Evolution of sales over time.
-   **Top Performing Cities**: Identification of cities with highest sales.

### Project Goals

-   **Visualize Sales Performance**: Create an intuitive dashboard to track key sales metrics.
-   **Identify Sales Trends**: Analyze sales patterns by region, product, and sales method.
-   **Enable Data-Driven Decisions**: Provide actionable insights for optimizing sales strategies.
-   **Showcase Power BI Skills**: Demonstrate end-to-end dashboard development from raw data to interactive visuals.

---

## What was done

This project involved the complete development of an Adidas Sales Power BI Dashboard:

### Data Acquisition & Transformation

-   Imported raw sales data from an Excel file.
-   Used **Power Query** to clean and transform data:
    -   Promoted first row as headers.
    -   Corrected data types (e.g., `Invoice Date` to Date, `Price per Unit` to Decimal Number).
    -   Created a `Month Year` calculated column for time-based analysis.

### DAX Measures

-   Developed core measures:
    -   `Total Sales` (SUM of Sales)
    -   `Units Sold` (SUM of Units)
    -   `Operating Margin` (AVERAGE of Operating Margin %)
-   A dedicated `_Measures` table was created to organize all DAX calculations.

### Dashboard Design & Visualization

-   Applied a custom Power BI theme for consistent branding.
-   **Overview Page**: Features KPI cards (Total Sales, Units Sold, Operating Margin %), donut charts for `Units Sold by Sales Method`, stacked column charts for `Sales by Year/Quarter`, bar charts for `Sales by Retailer` and `Sales by Region`, a line chart for `Monthly Sales Trend`, and a matrix for `Top 5 Performing Cities`.
-   Implemented interactive slicers for `Product`, `Retailer`, `Sales Method`, `Region`, `State`, `City`, and `Month Year` for dynamic filtering.
-   Applied conditional formatting (data bars) to the `Top 5 Cities` matrix for enhanced readability.
-   Ensured a clean, user-friendly layout with appropriate titles, labels, and background elements.

<!-- Placeholder for a screenshot of a specific visual or the dashboard in action -->
<!-- Example: ![Sales by Product Visual](https://github.com/your-username/your-repo/assets/your-image-id/sales_by_product.png ) -->


---

## Key Insights

The Adidas Sales Dashboard provides immediate insights into:

-   **Overall Performance**: Quick glance at total sales, units, and profitability.
-   **Sales Channel Effectiveness**: Understanding which sales methods (online, in-store, outlet) drive the most units.
-   **Geographical Performance**: Identifying high-performing regions and cities, as well as areas needing attention.
-   **Product Category Contribution**: Pinpointing top-selling product categories.
-   **Temporal Trends**: Observing monthly and quarterly sales patterns to inform forecasting and marketing campaigns.
-   **Retailer Performance**: Analyzing sales contribution from different retailers (e.g., Adidas, Amazon, Foot Locker).

