# data-analysis-spark-scala

# **Data Analysis with Spark and Scala**

This project demonstrates querying and analyzing entity-relationship data using **Apache Spark** with **Scala**. The data was processed in a distributed environment using **CloudXLab**, **HDFS**, and **Jupyter Notebooks**.

---

## **Technologies Used**

- **Apache Spark**: For distributed data querying and analysis.
- **Scala**: Programming language for Spark operations.
- **HDFS (Hadoop Distributed File System)**: Distributed storage for large-scale data management.
- **Jupyter Notebook**: Interactive platform to execute Spark and Scala code.
- **CloudXLab**: Cloud-based lab for distributed computing tasks, integrating Spark and HDFS.

---

## **Project Overview**

The project focuses on analyzing sales, orders, and customer data using Spark transformations and actions. It involves reading multiple CSV files from HDFS and performing data aggregation, filtering, and query operations.

Key tasks include:

1. **Customer Order Analysis**
   - Counting the number of orders placed by each customer.

2. **Sales Aggregation**
   - Total and average sales by customer and year.
   - Number of orders grouped by month and year.

3. **Product Analysis**
   - Identifying the most frequently ordered product for each customer.
   - Finding the bottom 3 customers with the fewest orders.

4. **Discount Analysis**
   - Analyzing patterns in orders with and without discounts. Around 38% of all orders received discounts.

5. **Entity Relationships**
   - Understanding data relationships across tables such as **Orders**, **OrderDetails**, **Customers**, and **Products**.
