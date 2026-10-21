
# Sales, Customer & Business Operations Analytics Dashboard | Power BI

## 1. Project Overview

An interactive **Power BI Business Intelligence Dashboard** designed to analyze sales performance, profitability, customer behavior, geographic sales distribution, and operational metrics.

The report consolidates key business indicators into four report pages, helping users explore performance trends, compare customer segments, identify important products, and evaluate supplier and marketing-channel performance.

## 2. Project Objectives

The main objectives of this project are to:

- Monitor overall revenue, profit, and average order value.
- Track sales and order trends over time.
- Analyze geographic performance across cities and locations.
- Understand customer segments and purchasing behavior.
- Compare product-level sales and profitability.
- Examine supplier dependency and marketing-channel contributions.
- Support data-driven business decisions through interactive visualizations.

## 3. Tech Stack

- **Power BI Desktop** — Dashboard development and data visualization
- **Power Query** — Data preparation and transformation
- **DAX (Data Analysis Expressions)** — Measures and business calculations
- **Data Modeling** — Relationships between business entities
- **Microsoft Azure Maps visual** — Geographic sales analysis

## 4. Data Sources and Data Model

The report contains data-model entities related to the following business areas:

- Customers
- Products
- Suppliers
- Orders
- Returns
- Marketing Campaigns
- Website Traffic
- Date Table
- Measures Table

The original external data-source URL and underlying source files could not be confirmed from the report metadata alone.

**Key measures and fields include:**
- Total Revenue
- Total Sales
- Total Profit
- Average Order Value
- Total Orders
- Previous Month Sales
- Previous Month Orders
- Supplier Dependency %
- Customer Segment
- Marketing Channel

## 5. Dashboard Pages and Key Features

### Page 1: Executive Dashboard

Provides a high-level overview of business performance.

**Key features:**
- KPI cards for Total Revenue, Total Profit, Average Order Value, and Customer ID.
- Monthly sales trend visualization.
- Geographic performance comparison.
- Product performance table featuring revenue, sales, and profit.
- Previous-month sales and order KPIs.
- Product and order-related summary indicators.

**Business value:** Helps decision-makers quickly review business performance, monitor trends, and identify products contributing to sales and profitability.

### Page 2: Geographic Sales

Focuses on location-based sales and profit analysis.

**Key features:**
- City-level sales comparison using a bar chart.
- Sales distribution by city using a donut chart.
- Interactive Azure Maps visualization using city, address, and sales information.
- Geographic comparison of Total Sales and Total Profit.

**Business value:** Helps identify high-performing locations, compare regional contributions, and explore geographic patterns in business performance.

### Page 3: Customer Analytics

Analyzes customer behavior and performance across customer segments.

**Key features:**
- Comparison of Total Sales and Total Profit by customer segment.
- Customer-level table with Total Orders and Total Sales.
- Treemap showing order distribution by customer segment.
- City slicer for filtering customer analysis.

**Business value:** Supports customer segmentation, identification of valuable customers, and comparison of purchasing activity across different groups and locations.

### Page 4: Operationals

Provides product, supplier, and marketing-channel performance insights.

**Key features:**
- Customer-level operational table showing Total Orders and Total Sales.
- Product-level Supplier Dependency % comparison.
- Product performance comparison using Total Sales and Total Profit.
- Marketing-channel sales distribution using a donut chart.

**Business value:** Helps assess product performance, investigate supplier dependency, and understand which marketing channels contribute to sales.

## 6. Business Problems Addressed

This dashboard is designed to help address common business reporting challenges:

- **Limited performance visibility:** Consolidates important KPIs into a single report.
- **Unclear sales trends:** Provides time-based sales and order comparisons.
- **Geographic performance gaps:** Makes city-level performance easier to compare.
- **Limited customer insight:** Highlights customer-level metrics and segment differences.
- **Product profitability questions:** Compares product sales and profit.
- **Operational dependency risks:** Visualizes supplier dependency by product.
- **Marketing performance uncertainty:** Compares sales contributions by channel.

## 7. Interactive Features

- Interactive charts and cross-filtering between visuals.
- KPI cards for quick performance monitoring.
- City-based filtering on the Customer Analytics page.
- Geographic exploration using Azure Maps.
- Customer, product, and segment-level comparisons.
- Report-page navigation buttons.

*Note: The exact filtering behavior depends on the visual interactions configured in Power BI.*

## 8. Screenshots and Demo

Add screenshots of your actual report pages to the repository to showcase the dashboard.

Suggested folder structure:

```text
demo-data-powerbi/
├── demo data.pbix
├── README.md
└── screenshots/
    ├── executive-dashboard.png
    ├── geographic-sales.png
    ├── customer-analytics.png
    └── operationals.png
```

After adding the screenshots, display them in this section:

### Executive Dashboard
![Executive Dashboard](https://github.com/itshemanthb/pbi-demo-salesanalysis-dax-powerquery-kpi/blob/main/main%20img1.png)

### Geographic Sales
![Geographic Sales](https://github.com/itshemanthb/pbi-demo-salesanalysis-dax-powerquery-kpi/blob/main/geographic%20img2.png)

### Customer Analytics
![Customer Analytics](https://github.com/itshemanthb/pbi-demo-salesanalysis-dax-powerquery-kpi/blob/main/customers%20img3.png)

### Operationals
![Operationals](https://github.com/itshemanthb/pbi-demo-salesanalysis-dax-powerquery-kpi/blob/main/operational%20img4.png)


## 9. Project File

| File | Description |
|---|---|
| `demo data.pbix` | Power BI report containing the dashboard pages, visuals, and data model |
| `README.md` | Project documentation |
| `screenshots/` | Folder for report screenshots |

## 10. Tools Required

- Microsoft Power BI Desktop
- DAX for measures and calculations
- Power Query for data transformation
- Access to the underlying data sources, if a refresh is required

## 11. Key Takeaways

This project demonstrates how Power BI can bring together sales, customer, geographic, product, supplier, and marketing metrics in one interactive reporting solution.

It showcases practical business intelligence techniques, including KPI monitoring, trend analysis, customer segmentation, geographic visualization, product profitability analysis, and operational performance reporting.

## 12. Author

**Hemanth B**

If you find this project useful, consider giving the repository a ⭐ on GitHub!
