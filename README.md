FMCG Retail Data Analytics
-------------------------------------------------------------
The Supermart Grocery Sales - Retail Analytics Dataset is that contains data on orders placed by customers using a grocery delivery application in the state of Tamil Nadu, India.
The dataset is a useful resource for understanding consumer behavior in the grocery retail industry, and for developing insights into the factors that drive sales in this sector.

By analyzing the dataset, data analysts can identify patterns, trends, and correlations that can help retailers optimize their marketing, pricing, and product strategies to increase sales and revenue.

### Data Description

| #  | Column        | Dtype   | Description                     |
|----|---------------|---------|---------------------------------|
| 0  | Order ID      | object  | Unique order entry identifier   |
| 1  | Customer Name | object  | Name of customer                |
| 2  | Category      | object  | Category of product             |
| 3  | Sub Category  | object  | Product Sub classifier          |
| 4  | City          | object  | Location of delivery - city     |
| 5  | Order Date    | object  | Date of order placement         |
| 6  | Region        | object  | Location of delivery - Region   |
| 7  | Sales         | int64   | Order value                     |
| 8  | Discount      | float64 | Offer given                     |
| 9  | Profit        | float64 | Profit generated from order     |
| 10 | State         | object  | Location of delivery - state    |

### Problem Description
Use the data to indentify patterns,trends and correlations to help retailers optimize their marketing, pricing and product strategies to increase sales and revenue.

### Process Description
Below is a summary of stages involved in the wrangling phase.

![Wrangling Process](./images/Wrangling%20Process.png)

 In this section we explore 5 high level business questions related to our data:

* What was the best month for sales? How much was earned that month?
* What city sold the most product?
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
* What products are most often sold together?
* What product sold the most? Why do you think it sold the most?