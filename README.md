# Superstore Sales Analytics Dashboard

An interactive analytics dashboard for exploring Superstore sales performance across regions, product categories, sub-categories, customer segments, and order dates.

## Dashboard Preview

<img width="1655" height="910" alt="Superstore Sales Analytics Dashboard" src="https://github.com/user-attachments/assets/492b2a7a-c042-43a4-9a4a-cc60e85db279" />


## Overview

This dashboard provides a consolidated view of Superstore sales, return rate, and profit margin. Users can filter the report by region and order year, and choose the metric displayed in the charts.

## Key Metrics

The dashboard header displays these KPI cards for the current filter selection:

- **Sales:** `₹22,97,200.86`
- **Return Rate:** `8.06%`
- **Profit Margin:** `12.47%`

These figures reflect the current view shown in the screenshot. They may change when filters or the selected metric change.

## Dashboard Visuals

### 1. Sales by Region
A column chart compares sales across the four regions:

- West — 725,458
- East — 678,781
- Central — 501,240
- South — 391,722

In the displayed view, West has the highest sales and South has the lowest.

### 2. Sales Trend Over Time
A line chart displays the selected metric by month of order date. A trend line helps reveal the overall direction of the series across the displayed period.

### 3. Top 5 Products by Sales
A horizontal bar chart ranks the five leading products by the selected metric. The visible top product is **Canon imageCLASS 2...**, with a displayed value of approximately **61,600**.

### 4. Sales by Sub-Category
A horizontal bar chart compares performance across product sub-categories. Phones and Chairs are among the highest displayed sub-categories.

### 5. Sales by Category
A column chart compares the three main product categories:

- Technology — 836,154
- Furniture — 742,000
- Office Supplies — 719,047

Technology has the highest displayed sales among these categories.

### 6. Sales by Segment
A pie chart shows the distribution across customer segments. The visible shares are approximately **50.56%**, **30.74%**, and **18.70%**.

## Filters and Interactivity

The dashboard includes:

- **Region filter:** All, Central, East, South, and West
- **Year of Order Date filter:** choose the years included in the analysis
- **Metric selector:** choose the metric used in supported charts

Use these controls to explore how performance changes across regions, years, and measures.

## Tools

- Tableau (dashboard layout and visual analytics)
- Superstore dataset (source dataset, if applicable)

Update this section to reflect the exact tools and data source used in your project.

## How to Use

1. Clone or download this repository.
2. Open the workbook in Tableau Desktop or Tableau Public, depending on the file format you provide.
3. If prompted, reconnect to the data source.
4. Use the region and order-year filters to focus the analysis.
5. Change the metric selector to compare available measures.

## Notes

- KPI and chart values shown above are taken from the screenshot and may change with filters.
- Confirm the currency, calculation definitions, and aggregation settings in the workbook before using these figures in formal reporting.
- Do not publish restricted business data or confidential information to a public repository.
