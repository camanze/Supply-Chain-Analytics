# Supply-Chain-Analytics
A Data-Driven Analysis of a Fashion &amp; Beauty Start-up

## **Introduction** 

Supply chain analytics plays a pivotal role in optimizing operations, reducing costs, and improving profitability. This project analyzes the supply chain of a Fashion & Beauty startup, focusing on makeup products, to uncover key insights into revenue trends, supplier performance, logistics efficiency, and product demand. Using Power BI, I transformed raw supply chain data into actionable business intelligence, helping stakeholders make informed decisions.

**Data Source**

The dataset for this project was obtained from the **Kaggle**. [Access it here](https://www.kaggle.com/datasets/amirmotefaker/supply-chain-dataset).

The dataset is based on the supply chain of Makeup products, presented in 24 columns of a CSV file. Below are all the features in the dataset:

Product Type,
SKU,
Price,
Availability,
Number of products sold,
Revenue generated,
Customer demographics,
Stock levels,
Lead times,
Order quantities,
Shipping times,
Shipping carriers,
Shipping costs,
Supplier name,
Location,
Lead time,
Production volumes,
Manufacturing lead time,
Manufacturing costs,
Inspection results,
Defect rates,
Transportation modes,
Routes,
Costs.

### **Data Exploration**  

The raw dataset, as downloaded, did not require extensive or major cleaning operations. I imported the dataset into Power BI and used Power Query to execute all pre-analysis cleaning required, like changing data types for some columns, formatting the data structure of some columns, creating a Date table and adding a relationship between the Date and supply_chain_data tables, creating a new table for Measures and writing DAX formulae for the measures.



### **Visualization and Analysis in Power BI**

The dataset includes:

- **Financial Metrics:** Total revenue (577K),costs (577K),costs(58K), and profit margins (86.07% avg).

- **Product Data:** 46,099 products sold, stock levels (4,777 units), and defect rates by category.

- **Geographic & Demographic Insights:** Revenue distribution across top cities (Mumbai, Kolkata, Chennai) and customer segments (Female: 27.96%, Male: 21.92%).

- **Supplier & Logistics:** Lead times, transportation costs, and defect rates across shipping carriers (Road, Rail, Sea, Air).

To explore the interactive Power BI dashboards, [Click Here](https://app.powerbi.com/view?r=eyJrIjoiMWU1MmRjODAtMGI4Yi00NTUwLTkyNmYtMDgxMWQyMmI4NDMyIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9). The visuals are spread across three pages, and the design incorporates user-friendly navigation features for seamless exploration. 

The Interactive dashboards were built to highlight:

- **Revenue Trends:** Skincare dominated sales ($0.24M), followed by haircare and cosmetics. Below is the Overview page of the Power BI visuals to highlight the revenue trends;

![Overview](https://github.com/user-attachments/assets/78b15dfc-1ec3-4f12-93f8-20213284c2b8)

The Product Insight page equally has a lot of information to highlight the revenue trends. Take a look;

![Product Insight](https://github.com/user-attachments/assets/d34b57bb-936d-4c08-896c-538001bbe17f)

- **Supplier Performance:** Supplier 3 had the highest profit margin (91.08%) but also higher defect rates.

- **Logistics Efficiency:** Carrier B generated the most revenue ($0.25M), but Carrier A had lower defect rates. Take a look at the Supplier Insight;

![Supplier Insight](https://github.com/user-attachments/assets/c98b5ce5-70d0-4f82-9d43-038c839f61cf)

## **Key Findings**

1. **Profitability:** High avg. profit margin (86.07%) indicates strong pricing strategy, but defect rates (up to 36.86% in haircare) need improvement.

2. **Supplier Risks:** Supplier 3 delivers high margins but has quality control issues—balancing cost and quality is critical.

3. **Logistics Optimization:** Sea transport had the highest defect rates (25.5%), suggesting a need for better handling or alternative carriers.

4. **Demand Insights:** Skincare outperformed other categories, while cosmetics had the lowest defect rates (28.49%).

5. **Demand Hotspots:** Mumbai and Kolkata were top revenue-generating cities.

## **Conclusions**

This analysis reveals opportunities to enhance supplier partnerships, reduce defects, and optimize logistics for greater efficiency. The startup’s strong profitability is promising, but targeted improvements in quality control and carrier selection could further boost margins.

## **Recommendations**

✅ **Supplier Collaboration:** Work with Supplier 3 to reduce defects while maintaining high margins.

✅ **Logistics Audit:** Investigate high defect rates in sea shipments and explore alternative carriers.

✅ **Inventory Strategy:** Increase stock for high-demand products (skincare) in top cities (Mumbai, Kolkata).

✅ **Predictive Analytics:** Implement forecasting models to anticipate seasonal demand shifts.
