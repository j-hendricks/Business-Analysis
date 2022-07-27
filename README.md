# Business-Analysis

## Overview

An anonymous business has shared its sales data (2017-2019) on the website Kaggle. The goal of this project is to determine trends in the data. More specifically, the goal is to determine the following:

* Are sales increasing? 
* What products are selling the most?
* What products are selling the least? 
* What products produce the highest revenue per sale?
* Do higher discounts result in more products sold? What about total net sales? 
* What time of the year has the highest sales?

To answer these questions, Python and Jupyter Notebook were used, along with Pandas and Matplotlib. 

## Results

As seen in the bar graph below, the most frequently bought products are baskets, art & sculpture and jewelry. The least bought items are One-of-a-kind, textiles and furniture. Similarly, most of the discounts and returns are derived from baskets, art & sculpture and jewelry. However, when it comes to percent return, textiles have much higher returns on average, and Easter and furniture products have the highest percent discounts.  

![bar_quantity](bar_quantity.png)
![bar_returns](bar_returns.png)
![bar_discount](discount.png)

The figure below plots the average net loss per month. In this project, we have defined net worth as the amount of the gross sales lost from discounts and returns. The figure shows no clear patterns. However, there seems to be a large spike in net loss during the beginning months of 2017 and 2019. The large spikes in discounts appear to be spaced by several months of low net loss.

![bar_revenue_per_item](bar_revenue_per_item.png)

This figure shows the amount of monthly discounts overtime. The number skyrockets near the end of 2019, but is stable otherwise. Thus, the fluctuation in net loss is due to returns, which is demonstrated in the second figure below.

![time_discounts](time_discounts.png)
![time_returns](time_returns.png)

From the large amount of overlap in the plot below, it is evident that the  majority of the money loss came from returns and not discounts. There was a huge spike in net loss and returns in the early summer of 2018. There were also many order occuring that month, which would explain the sudden increase in returns.

![time_comparison](time_comparison.png)

Annual sales are increasing. The percent increase from 2017 to 2019 is roughly 50%. This is fantastic new for the company! From the line plot, it seems that the sales always jump during the end of the year, which right around Christmas time. 

![bar_sales](bar_sales.png)
![time_yearly](time_yearly.png)


![scatter_sales](scatter_sales.png)



## Conclusion

The company entered a unusually profitable quarter during the winter months of 2019. The most commonly bought products were baskets, art & sculpture and jewelry. The product that produced the most revenue per item sold was the "One-of-a-kind" product line, which was one of the least sold items.
