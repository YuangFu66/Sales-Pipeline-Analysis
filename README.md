# Sales-Pipeline-Analysis
<img width="1185" height="657" alt="image" src="https://github.com/user-attachments/assets/78f816d3-93be-4b96-baf7-bb3eed1a0aeb" />

## **Project Overview**

The goal of this project is to analyze a company’s **sales pipeline**, uncovering insights into total revenue, win rates, agent performance, and product profitability by using the **SQL** and **Power BI**.

The dataset, provided by Maven Analytics, simulates CRM sales data containing detailed information on sales opportunities, products, deal stages, close values, and sales representatives. It tracks every step of the sales funnel — from initial engagement to deal closure — allowing both time-series trend analysis and cross-sectional comparisons by product, agent, and region.

The analysis was conducted in **two main phases**:
1. **Data Processing & KPI Calculation in Snowflake SQL** – cleaning, transforming, and aggregating raw CRM data to compute key metrics such as monthly opportunities, win rates, and total revenue.
2. **Dashboard Design in Power BI** – visualizing these insights through interactive charts

## **Key Features**

- **Total Revenue and Win Rate KPIs** displayed at a glance  
- **Product Performance:** Revenue and win rate breakdown by product category  
- **Sales Agent Insights:** Agent-level revenue and deal success metrics  
- **Trend Tracking:** Monthly revenue and win rate trends to assess pipeline consistency  
- **Geographic Analysis:** Total revenue visualized by office location using an interactive map  
- **Interactive Filtering:** Ability to filter by sales agent and product

## **Tools & Technologies**

- **Snowflake SQL** – for data cleaning, transformation, and KPI computation  
- **Power BI Desktop** – for data modeling, visualization, and interactive dashboard design  
- **DAX** – for additional calculated measures and custom KPIs  
- **Microsoft Excel / CSV** – for initial dataset preparation and validation  


## **Insights & Findings**

- **Total Revenue:** The company achieved approximately **$10.01 million** in total closed deals, reflecting strong sales execution and consistent revenue generation across key product lines and regions.  

- **Overall Win Rate:** The **63.15% win rate** indicates that nearly two-thirds of all sales opportunities converted successfully. While performance is solid, monthly fluctuations suggest room to improve consistency through enhanced sales training and pipeline management.  

- **Top Product:** **GTX Pro** led performance with **35.09% of total revenue**, highlighting its strong market demand and strategic importance. However, this reliance also signals the need to diversify revenue across additional product lines.  

- **Top Sales Agent:** **Darcel Schlereth** was the highest-performing agent, outperforming peers in both total revenue and conversion rate. Her results suggest strong client relationships and efficient deal management that could serve as a model for the wider team.  

- **Regional Performance:** **North America** generated the majority of total revenue, demonstrating mature market presence and higher conversion efficiency compared to other regions, where localized strategies could unlock further growth potential.  

- **Monthly Trends:** Monthly data revealed visible fluctuations in win rates and revenue, likely influenced by campaign timing and seasonality. Addressing these patterns could help stabilize quarterly performance and enhance forecasting accuracy.  


## **References**

- **Maven Analytics Project:** [Sales Pipeline Analysis](https://app.mavenanalytics.io/guided-projects/3a35f0ec-fc19-4e69-8377-b08534925844)  
- **Dataset provided by Maven Analytics**  
- **SQL Script:** [`Sales_KPI.sql`](./Sales_KPI.sql)  
- **Power BI Dashboard File:** [`Sales Pipeline Analysis.pbix`](./Sales%20Pipeline%20Analysis.pbix)  
