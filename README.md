# Horizon Retail Group | Excel Executive Dashboard Case Study

## Business Background & Problem Statement

Horizon Retail Group is a multi-region retail company operating across Central, East, South and West markets with diversified product categories including Furniture, Office Supplies and Technology.

As transaction volume scaled, leadership faced limited centralized visibility into revenue performance and operational efficiency.

### Key challenges included:

- No consolidated KPI reporting structure.

- Fragmented regional performance tracking.

- Limited insight into product-level revenue concentration.

- Lack of structured year-over-year sales monitoring.

- No measurable view of delivery efficiency or repeat order behavior.

### Leadership required a structured analytics solution to:

- Centralize financial performance reporting.

- Quantify revenue by region, segment, and category.

- Identify top-performing products.

- Monitor yearly growth trends.

### Data Model & Preparation

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Superstore%20Messy%20dataset.png)

Horizontal Retail Group Raw Transaction Dataset

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Superstore%20Cleaned%20Dataset.png)

Horizontal Retail Group Dataset after cleaning and transform using Power Query. 

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Pivot%20Tables%20.png)

Pivot Table View 

### Data preparation included:

- Cleaning and standardization using Power Query

- Structuring time intelligence fields (Year extraction)

- Creating KPI calculations layer

- Building normalized Pivot Tables to power dashboard visuals

- Executive Dashboard Overview

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Superstore_Dashboard.png)

The final Excel dashboard integrates interactive slicers and KPI cards to provide a centralized performance monitoring system.

### Core KPI Metrics:

- Total Sales: 397K+

- Unique Orders: 1,722

- Average Order Value: 230.7

- Average Delivery Time: 3.96 Days

### Revenue Performance Insights:

Yearly Sales Trend

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Yearly%20Sales%20Trend%20.png)

Sales demonstrate steady year-over-year growth through 2018, indicating positive revenue momentum.

Sales by Region

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Sales%20by%20Region.png)

Sales are distributed across all four regions, with East accounting for the largest share (30%) followed by West (28%), indicating moderate regional concentration.

Sales by Category & Sub-Category

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Sales%20by%20Category%20%26%20Sub-category.png)

Technology leads overall revenue contribution, with identifiable high-performing sub-categories driving category dominance.

Customer Segment Contribution

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Sales%20by%20Segments.png)

The Consumer segment contributes the largest share of total revenue, followed by Corporate and Home Office.

Top 10 Products by Revenue

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Top%2010%20products%20by%20revenue%20.png)

Revenue is partially concentrated among high-performing SKUs, allowing inventory and product prioritization decisions.

Sales by State

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/Sales%20by%20States.png)

State-level analysis highlights geographic revenue concentration and underperforming territories.

### KPI Calculation Framework

![Alt text](https://github.com/Shahimti/Excel-Superstore-Dashboard/blob/main/project_images/KPI%20Calculations.png)

A dedicated KPI layer was created to support executive-level monitoring, including:

- Repeat Customer Count

- Segment-specific Revenue

- Region-specific Revenue

- Year-specific Sales

- Average Delivery Time

This structured calculation framework ensures dashboard scalability and reporting consistency.

### Intended End User & Business Application

This dashboard is designed for:

- Regional Sales Managers

- Operations Leadership

- Finance & Reporting Teams

It supports:

- Monthly performance reviews

- Revenue trend monitoring

- Product portfolio analysis

- Regional performance comparison

- Operational efficiency tracking

The model enables leadership to transition from static reporting toward interactive financial oversight.

Based on the analysis, Horizon Retail Group leadership can:

- Prioritize high-performing product categories

- Optimize inventory toward top-selling SKUs

- Allocate marketing efforts to dominant revenue segments

- Improve delivery performance

- Identify underperforming states for targeted sales initiatives

### Assumptions & Limitations:

- Sales values represent gross revenue (not profit).

- Delivery time calculated as ship Date minus order Date.

- Analysis focuses on revenue metrics rather than margin modeling.

