# Clothing-Store_Dashboard_by_POWER_BI

![](-)
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

### 🧮 Data Cleaning and Data Processing :

- Age group,Mounth;
```
- Age group=IF(E2>=50,"Senior",
        IF(E2>=30,"Adult","Teenager"))
  
- Mounth=TEXT(G2,"mmm")
```

### 📉 Charts and Visualization :

The report comprises 6 charts:

___1. Orders vs Sales;___

___2. Sales : Men vs Women;___

___3. Orders Status;___

___4. Sales : Top 5 States;___

___5. Relation between age and gender;___

___6. Orders : Channels.___

we're use the pivot table for every shart

__- Features:__
- Order Date by Mounth Timeline;
- Channel Slicer;
- Category Slicer.

 the all dashboard ![](-)

___1. Orders vs Sales;___

![](-)

_March, January and February are the months which marked the top sales with ___1.92 M,1.88 M and 1.82 M___ sum of amount and ___2819,2750 and 2720___ orders. 🤓_

___2. Sales : Men vs Women;___

![](-)

_Women are more likely to buy compared to men with 65% . 🤓_

___3. Orders Status;___

![](-)

_this store deliver in 2022 more than ___28641___ orders . 🤓_

___4. Sales : Top 5 States;___

![](-)

_MAHARASHTRA,KARNATAKA and UTTAR PRADESH are the top 3 states with 69,54 % . 🤓_

___5. Relation between age and gender;___

![](-)

_Adult age group (30-49 yrs) is max contributing 50 %  . 🤓_

___6. Orders : Channels.___

![](-)

_Amazon,Flipkart and Myntra channels are max contributing 80 % . 🤓_

### ❎ Conclusion and Recommendations:

Target __Women__ customers of age group __30-49__ yrs living in ___MAHARASHTRA,KARNATAKA and UTTAR PRADESH___ by showing ads/offers/coupons available on ___Amazon,Flipkart and Myntra___. 😄

