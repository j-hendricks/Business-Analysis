# Business-Analysis

## Overview

An anonymous business has shared its sales data (2017-2019) on the website Kaggle. The goal of this project is to determine trends in the data. More specifically, the goal is to determine the following:

* Are sales increasing? 
* What products are selling the most?
* What products are selling the least? 
* What products produce the highest revenue per sale?
* Do higher discounts result in more products sold? What about total net sales? 

To answer these questions, Python and Jupyter Notebook were used, along with Pandas and Matplotlib. 

## Results

As seen in the bar graph below, the most frequently bought products are baskets, art & sculpture and jewelry. The least bought items are One-of-a-kind, textiles and furniture.

As the amount discounted is increased, the quantity sold per order increased and the amount of revenue increased as well. The r value was 0.839 for the latter relationship, meaning there is a very strong correlation discount and revenue made. As a result, discounts on products should be encouraged in moderation. 

From the large amount of overlap in the plot below, it is evident that the  majority of the money loss came from returns and not discounts. There was a huge spike in net loss and returns in the early summer of 2018. An analysis should be initiated to determine what caused this high return rate - was it just by chance, or did employees recommend the wrongs products to customers? 

![time_comparison](time_comparison.png)

Sales have increased remarkably in the winter of 2019. However, it is difficult to determine what led to this change.
![time_yearly](time_yearly.png)

The product with the highest revenue per item sold is the "One-of-a-kind" selection. However, given the small quanitity sold, this could just be a coincidence.  

## Conclusion

The company entered a unusually profitable quarter during the winter months of 2019. The most commonly bought products were baskets, art & sculpture and jewelry. The product that produced the most revenue per item sold was the "One-of-a-kind" product line, which was one of the least sold items.
