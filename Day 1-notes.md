
# Day 01 - Introduction to Data Engineering

## 1. What is Data Engineering?

Data Engineering is about collecting, cleaning, processing, and storing data.

Companies collect data from different sources such as websites, applications, databases, and customer transactions.

This data cannot always be used directly. It needs to be organised and processed before it becomes useful.

A Data Engineer builds systems and pipelines to perform these tasks.

**Example:**

An online shopping company receives customer orders every day. A Data Engineer helps collect the order details, remove incorrect records, and store the data for further analysis.

## 2. What does a Data Engineer do?

The main work of a Data Engineer is to make data available and ready to use.

Some important responsibilities:

- Collect data from different sources.
- Clean incorrect and duplicate records.
- Transform data into the required format.
- Store data in databases or data warehouses.
- Build automated data pipelines.
- Check data quality and pipeline failures.

**Technologies used:**

- SQL - Working with databases.
- Python - Processing and automating data.
- Azure - Cloud services.
- Microsoft Fabric - Data engineering and analytics.
- PySpark - Processing large amounts of data.

## 3. Difference Between Data Engineering, Data Analytics and Data Science

I understood the difference using an online shopping example.

**Data Engineering:**
Collects, processes, and stores customer order data.

**Data Analytics:**
Uses the collected data to understand sales, revenue, and popular products.

**Data Science:**
Uses historical data and machine learning to predict customer behaviour.

In simple terms:

- Data Engineer prepares the data.
- Data Analyst analyses the data.
- Data Scientist builds predictive models using data.

## 4. What is a Data Pipeline?

A data pipeline is a process of moving data from one place to another.

During this process, data can also be cleaned and transformed.

**Example:**

An online shopping company collects order details from its application.

The data goes through these steps:

1. Collect order data.
2. Clean the data.
3. Transform the data.
4. Store it in a data warehouse.
5. Use it for reports.

This complete process is called a data pipeline.

## 5. What is ETL?

ETL stands for:

- Extract
- Transform
- Load

I understood ETL as collecting data, making it clean and useful, and then storing it.

**Example:**

1. Extract: Get sales data from a CSV file.
2. Transform: Remove duplicate records and correct missing or incorrect values.
3. Load: Store the cleaned data in a database.

The order is:

Extract → Transform → Load

In ELT, data is first collected and loaded into the destination. Transformation happens afterwards.

**Example:**

1. Extract raw sales data from a source.
2. Load the raw data into a cloud data warehouse.
3. Transform the data using SQL or Spark.

The order is:

Extract → Load → Transform

## 6. What I Learned Today

- Understood what Data Engineering means.
- Learned the responsibilities of a Data Engineer.
- Understood the difference between Data Engineering, Analytics, and Data Science.
- Learned how a data pipeline works.
- Understood the basic concepts of ETL and ELT.
- Learned the difference between databases, data lakes, and data warehouses.

