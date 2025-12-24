# Pizza-Sales-Analysis
End-to-end data analysis using MySQL and Power BI●● Pizza Sales Analysis🍕

● Objective
To analyze pizza sales data and identify order patterns, top-performing pizzas,
and revenue distribution using SQL and Power BI.

● Dataset
The dataset consists of four relational tables:
- Order_Details (order_details_id, order_id, pizza_id, quantity)
- Orders (order_id, date, time)
- Pizzas (pizza_id, pizza_type_id, size, price)
- Pizza_Types (pizza_type_id, name, category, ingredients)

● Tools Used
- MySQL – data validation, joins, aggregations, KPI preparation
- Power BI – KPI cards, interactive charts, and dashboard visualization

● Workflow
MySQL was used to examine and validate the data required for KPI calculations such as total orders, total sales, and total pizzas sold. After verifying the accuracy of metrics and aggregations, the prepared dataset was exported to Power BI. Power BI was then used to create KPI cards and interactive visualizations.

● Key Analysis Performed
- Total orders, total sales, and total pizzas sold (KPI cards)
- Order distribution by hour of the day
- Top pizzas by quantity sold
- Top pizzas by revenue generated
- Orders by day of the week
- Total sales by pizza category
- Order distribution by time slot (Morning, Afternoon, Evening, Night)
- Sales analysis by pizza size using slicers

● Dashboard Preview
<img width="1350" height="756" alt="Screenshot 2025-12-24 100713" src="https://github.com/user-attachments/assets/ec2da036-30a7-42ce-ba04-75367c4def19" />


● Conclusion
The analysis reveals consistent ordering patterns and clear revenue drivers within the pizza sales data. Afternoon and evening time slots contribute the highest number of orders, while Fridays record the peak order volume during the week. Classic and Supreme categories generate the highest sales, indicating strong customer preference. A small group of top-performing pizzas contributes a significant portion of both total quantity sold and revenue. Overall, the dashboard highlights how order timing, product category, and pizza size collectively influence sales performance, demonstrating the value of data-driven insights for business decision-making.
