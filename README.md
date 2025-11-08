# 📊 Ecommerce 13-Week Sales Analytics Dashboard

**Advanced Power BI Solution with Dynamic DAX and Interactive Visualizations**

***

## About This Project

This ecommerce sales dashboard project gave me the opportunity to combine deep analytical skills with business insight. Its purpose is to empower sales, marketing, and operations teams with clear, timely, and actionable insights that drive growth and efficiency across channels.

Through a thoughtfully designed data model and powerful DAX calculations, this dashboard turns weekly ecommerce sales data into compelling, easy-to-digest visuals that help uncover trends, customer behaviors, and operational bottlenecks.

***

## Problem Statement

The ecommerce industry faces constant challenges managing sales trends, customer satisfaction, fluctuating order volumes, and delivery performance. Without real-time, comprehensive analytics covering multiple dimensions such as product popularity, gender splits, and delivery times, strategic decisions can be delayed or misguided.

***

## Objectives

- Create a scalable, reusable dashboard supporting flexible user queries over 13 weeks of sales data.
- Surface meaningful KPIs: orders, quantity, amount, average delivery times, and customer ratings.
- Enable time-trend analysis with drill-downs by product, region, customer gender, and order channel.
- Visualize customer satisfaction and delivery duration to highlight performance and issues.
- Promote quick decision making with interactive slicers and intuitive visuals.

***

## Dataset Description

- **Transactions Table:** Sales transactions with info on products, customer demographics, order modes, quantities, amounts, ratings, and delivery dates.
- **Date Table:** Calendar table enriched with day, week, and month metadata for time intelligence.

Relation established between transaction dates and calendar dates to enable context-aware analytics.

***

## Methodology

- Data ingested and cleaned using Power Query and Excel.
- Star-schema modeling with separate date and transaction tables.
- Extensive DAX for KPIs, trends, percentages, and conditional logic.
- Interactive elements including slicers and drill-throughs for granular user exploration.
- Clean and professional report layout emphasizing readability and business focus.

***

## Dashboard Features

- **KPI Cards:** Total orders, total quantity, total amount, average days to deliver, and average rating.
- **Sales Trends:** Line chart showing order and amount trends over 13 weeks.
- **Order Mode Breakdown:** Pie and bar charts illustrating sales by channel and customer gender.
- **Product Popularity:** Horizontal bar visual ranking products by total sales.
- **Geographic Distribution:** Map visualization showing sales volume by county.
- **Customer Satisfaction:** Bar chart on customer happiness segmented by gender.
- **Delivery Duration:** Column chart detailing distribution of delivery times.
- **Monthly Orders & Ratings:** Comparative chart of orders and rating trends across months.

🔗 Live Dashboard
Explore the interactive dashboard here:
👉 [  View   ](https://app.powerbi.com/view?r=eyJrIjoiNDMzMDk5NjMtM2Y1ZC00MTU1LTkzNTQtMjEzNWJkYTM5ZjJmIiwidCI6ImRjODhkNWNiLWMxMjEtNDUzYi1hMGRiLTFmMzlmYjEyMjJiMyJ9)

***
## Data & Tools
- **Dataset:** Cleaned ecommerce transaction data covering 13 weeks.
- **Tools:** Power BI (Desktop/Service), DAX, Power Query, Excel for support.
- **Skills Demonstrated:** Data modeling, advanced DAX, data cleaning, visualization, dashboard design.
*** 
## Key Visuals
- Line, bar, column, and pie charts
- Card KPIs
- Geographic map visualizations
- Drill-down tables and custom tooltips

*** 
## Sample DAX Measures

```DAX
Total Orders = DISTINCTCOUNT('Sales'[TransactionID])

Total Quantity = SUM('Sales'[Quantity])

Avg Days to Deliver = AVERAGE('Sales'[DeliveryDays])

Customer Satisfaction Avg = AVERAGE('Sales'[Rating])

Orders by Channel = CALCULATE([Total Orders], ALLEXCEPT('Sales', 'Sales'[OrderMode]))
```

***

## Model Design Principles

- Star-schema for flexibility and performance.
- Clear, descriptive measure names with comments.
- Dynamic calculations influenced by slicers and time filters.
- Focused visual design for business effectiveness.

***

## Final Thoughts

This project is the culmination of focused learning, problem-solving, and application of analytics best practices. It reflects my growth in Power BI, DAX, and business intelligence storytelling.

I am excited to leverage these skills in future analytics challenges and deliver impactful solutions.

***

## Contact

Please reach out with any questions or collaboration interests:

[Satya Ganesh LinkedIn](https://www.linkedin.com/in/satya-ganesh-5a89b2283/)  

