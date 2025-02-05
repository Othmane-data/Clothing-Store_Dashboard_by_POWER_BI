# Clothing-Store_Dashboard_by_POWER_BI

![](https://github.com/Othmane-data/Clothing-Store_Dashboard_by_POWER_BI/blob/main/MY-OTH-DATA.pbix)
---
## Introduction

To conduct a comprehensive analysis of OTH-DATA Clothing sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

## Dashboard File

My final [dashboard](OTH-DATA.pdf)

## Problem statement

1. Analyze the impact of fat content on total sales.
2. Identify the performance of different item types in terms of total sales.
3. Compare total sales across different outlets segmented by fat content.
4. Evaluate how the age or type of outlet establishment influences total sales.
5. Analyze the correlation between outlet size and total sales. 
6. Assess the geographic distribution of sales across different locations. 
7. Provide a comprehensive view ot all key metrics ( total sales, Average Sales, Number ot Items, Average Hating) broken down by different outlet types. 

## Skills/ concepts demonstrated

- 🧮 Data Cleaning and Data Processing
- 📉 Charts and Visualization
- ❎ Conclusion and Recommendations

### 🧮 Data Cleaning and Dax :

- Total sales ;
```sql
Total Sales =

SUM
('BlinkIT Grocery Data (2)'[Sales])
```


- AVG Sales ;
```sql
Avg Sales =

AVERAGE
('BlinkIT Grocery Data (2)'[Sales])
```

- AVG Rating ;
```sql
Avg Rating =

AVERAGE
('BlinkIT Grocery Data (2)'[Rating])
```

- No of Items ;
```sql
No of Items =

COUNTROWS
('BlinkIT Grocery Data (2)')
```

- Metrics ;
```sql
METRICS =

{
    ("Total Sales", NAMEOF('BlinkIT Grocery Data (2)'[Total Sales]), 0),
    ("Avg Sales", NAMEOF('BlinkIT Grocery Data (2)'[Avg Sales]), 1),
    ("No of Items", NAMEOF('BlinkIT Grocery Data (2)'[No of Items]), 2),
    ("Avg Rating", NAMEOF('BlinkIT Grocery Data (2)'[Avg Rating]), 3)
}

```
### 📉 Charts and Visualization :

The report comprises 7 charts:

___1. Total Sales by Fat Content;___

___2. Total Sales by Item Type;___

___3. Fat Content by Outlet for Total Sales;___

___4. Total Sales by Outlet Establishment;___

___5. Sales by Outlet Size;___

___6. Sales by Outlet Location;___

___7. All Metrics by Outlet Type;___


 the all dashboard ![](OTH-DATA.pdf)



___1. Total Sales by Fat Content;___



___2. Total Sales by Item Type;___



___3. Fat Content by Outlet for Total Sales;___



___4. Total Sales by Outlet Establishment;___



___5. Sales by Outlet Size;___



___6. Sales by Outlet Location;___



___7. All Metrics by Outlet Type;___




### ❎ Conclusion and Recommendations:

Target __Women__ customers of age group __30-49__ yrs living in ___MAHARASHTRA,KARNATAKA and UTTAR PRADESH___ by showing ads/offers/coupons available on ___Amazon,Flipkart and Myntra___. 😄

