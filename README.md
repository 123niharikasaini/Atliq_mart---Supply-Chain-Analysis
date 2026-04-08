# Atliq Mart - Supply Chain Analysis

### Project Overview

This project presents a Supply Chain Analysis Dashboard built in Power BI for Atliq Mart, an FMCG manufacturer aiming to expand to other metros/Tier 1 cities in the next 2 years. The company is currently facing a problem where a few key customers have not extended their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service.

The objective of this dashboard is to analyze key supply chain service metrics and identify operational gaps that may be affecting customer satisfaction and order fulfillment.

### Purpose
ABC Mart plans to expand into metro and Tier-1 cities over the next two years. However, some key customers have not renewed their annual contracts due to service issues. It is suspected that certain essential products were not delivered on time or in full over an extended period, leading to poor customer service.

This dashboard provides insights into delivery performance and order fulfillment efficiency to support data-driven decision making.

### Tools & Technologies
1. Power BI Desktop
2. Power Query
3. DAX (Data Analysis Expressions)
4. Data Modeling
5. Data Visualization & KPI Monitoring

### Data Source
The dataset used in this project is provided by Codebasics from company’s supply chain team. It contains multiple tables capturing customer, product, line-level and order-level information.

##### Tables included in the dataset:

Customers – Contains details of customers such as customer names and city information.
Products – Includes product-level information used in the order transactions.
Target Orders – Defines the target key performance metrics set for each customers.
fact_order_lines – Contains order line level data such as product details, ordered quantity, agreed delivery date, and actual delivery date.
fact_order_aggregate – Includes aggregated order-level metrics such as order placement date and performance indicators like OT (On-Time), IF (In-Full), and OTIF (On-Time In-Full).

### Key Performance Indicators (KPIs)

The dashboard tracks critical supply chain metrics including:

On-Time Delivery (OT) % – An order-level metrics that determines if an order is delivered as per the agreed time with the customer.
In-Full Delivery (IF) % – An order-level metrics that determines if an order is delivered in full as per the requested quantity by the customer.
On-Time In-Full (OTIF) % – An order-level metrics that determines if orders delivered both on time and in full.
Volume Fill Rate (VOFR) – Total quantity shipped for a customer per order or for a given period of time.
Line Fill Rate (LIFR) – Determines how many lines shipped out of the total lines ordered by a customer.

### Dashboard Components

1. KPI Trend Analysis

Line charts showing historical trends for each key metric:
OT %
IF %
OTIF %
VOFR %
LIFR %

Each visualization includes a target value reference to compare actual performance with business expectations.

2. City-Level Insights

A city-wise performance table displaying the percentage values of all key metrics for each city.
This helps identify cities where service levels are below expectations.

3. Customer Order Analysis

A bar chart highlighting the Top 5 customers by total orders, helping understand major demand contributors.

4. Customer-Level Service Insights

A customer performance table presenting:

OTIF %
OT %
Target values

This helps identify customers whose service levels are not meeting the targeted benchmarks.

5. Product-Level Insights

A product performance matrix showing key metrics by product.
Sparklines are used to visualize monthly performance trends, enabling quick detection of improving or declining service levels.

