 **Sales Data Analysis**

 **Project Overview**
This project focuses on analyzing sales data to uncover insights related to revenue, profit, customer behavior, and regional performance. The analysis helps identify top-performing products, sales channels, and regions, supporting data-driven business decision-making.

  **Dataset Description**
The dataset contains transactional sales records with the following attributes:
- Date of sale
- Region and City
- Product and Product Category
- Customer Type
- Sales Channel
- Sales Representative
- Revenue, Cost of Goods Sold (COGS), and Profit

  **Data Preparation**
- Extracted the Month field from the Date column using "=TEXT([@Date],"MMMM")"
- Calculated Revenue,(=[@[Unit Price]]*[@Quantity]) Cost of Goods Sold (COGS) (=[@Quantity]*[@[Cost Price]]), and Profit (=[@Revenue]-[@COGS])
- Ensured accuracy and consistency of derived fields for analysis

  **Objectives**
- Analyze sales performance across regions and cities
- Identify top-performing products and product categories
- Compare revenue and profit across sales channels and customer types
- Evaluate sales representative performance
- Understand monthly sales trends

  **Key Insights**
- Identified regions and cities contributing the highest revenue and profit
- Analyzed product categories with the strongest sales performance
- Compared profitability across sales channels
- Highlighted top-performing sales representatives

  **Tools**
- Microsoft Excel
- Excel formulas and functions
- Pivot tables and charts

  **Conclusion**
This project demonstrates practical data analysis skills using Excel, including data preparation, metric calculation, and performance analysis. The insights generated can support strategic sales and business decisions.
