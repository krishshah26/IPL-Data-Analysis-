
# Ipl Data Analysis

**Overview**

This project demonstrates the use of Apache Spark for analyzing IPL (Indian Premier League) data. It covers a full data engineering workflow, from data ingestion and transformation to analysis and visualization. 

**Aim** 

 The goal of this project is to have hands-on experience with Spark and Databricks while exploring key insights from IPL datasets.

**Project Objectives**

- Understand and work with large-scale datasets using Apache Spark.
- Perform data transformations, including schema definition, type casting, and feature engineering.
- Analyze IPL data with SQL queries and derive meaningful insights.
- Visualize data for easier interpretation and presentation of results.
- Gain familiarity with Databricks as a development environment for Spark.

**Key Features**

- Data Storage: Data is stored on Amazon S3 for seamless integration with Spark.
- Environment: Databricks is used to execute and manage Spark jobs.
- Processing: Extensive use of PySpark for transformations and SQL for data analysis.
- Insights: Extraction of key metrics like top-scoring batsmen, toss impact, and team performance.
- Visualizations: Graphical representations of toss-win impact, dismissal types, and team statistics.





## Tech Stack

The following tools and technologies are used in this project:

**Core Technologies:**

- Apache Spark: For distributed data processing and analysis.
- Databricks: Cloud-based platform for running and managing notebooks and clusters.
- Amazon S3: To store IPL datasets.
- Programming Languages and Libraries
  - PySpark
  - SQL
  - Matplotlib

## Dataset
The IPL dataset contains detailed cricket data for seasons up to 2017.

*Download the dataset:*
https://data.world/raghu543/ipl-data-till-2017

## Workflow

**Setup:**
- Configure Databricks workspace.
- Set up the Amazon S3 bucket for data storage.
- Upload IPL datasets to the bucket.
**Data Ingestion:**
- Load datasets into Spark DataFrames.
- Define schemas using PySpark types like StructType and StructField.
**Data Transformation:**
- Clean and preprocess the data (e.g., casting data types, handling nulls).
- Perform feature engineering, such as calculating total and average runs.
**Analysis:**
- Convert DataFrames into SQL tables.
- Execute queries to derive insights, e.g., top-scoring batsmen, toss impact, and dismissal patterns.
**Visualization:**
- Create visualizations using Python libraries.
- Graph results like toss-winning performance and dismissal types.


## Future Enhancements

- Incorporate more recent IPL datasets for updated analysis.
- Enhance visualizations with interactive dashboards.
- Automate data ingestion and processing pipelines.
- Extend analysis to include advanced cricket metrics (e.g., Net Run Rate).


## 🚀 About Me
Hello! 👋 My name is Krish Shah, and I am a passionate Data Analyst and aspiring Data Engineer with a strong foundation in data-driven problem-solving and technical innovation. With a keen interest in leveraging technology to extract meaningful insights from complex datasets, I specialize in creating robust, scalable solutions for data analysis and visualization.

