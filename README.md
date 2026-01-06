#  Sales Analytics — Databricks & PySpark

##  Overview
This project analyzes multi-channel restaurant sales data using **PySpark on Databricks**.  
The objective is to understand product demand, customer behavior, sales trends, and revenue contribution across platforms such as Restaurant, Swiggy, and Zomato.

---

##  Tech Stack
- Databricks
- PySpark
- Databricks Visualization UI

---

##  Datasets
**sales dataset**
- Product_id  
- Customer_id  
- Order_date  
- Location  
- Source_order  

**menu dataset**
- Product_id  
- Product_name  
- Price  

---

##  Analysis Performed
- Created DataFrames for sales and menu datasets  
- Derived **Year, Month, Quarter** from Order_date  
- Calculated **total amount spent by each customer**  
- Calculated **total sales by food category**  
- Computed **monthly, yearly, and quarterly sales**  
- Found **total orders by each product**  
- Identified **Top 5 ordered items & Top ordered item**  
- Calculated **customer visit frequency**  
- Calculated **total sales by country**  
- Calculated **total sales by order source (Restaurant / Swiggy / Zomato etc.)**

---

##  Dashboard
A Databricks dashboard was created to visualize key KPIs.

# Exported dashboard file:
`Sales_analysis_project.html`


##  Key Outcomes
- Identified best-selling products  
- Analyzed customer purchasing patterns  
- Observed time-based sales trends  
- Understood channel-wise revenue contribution  


