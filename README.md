# Big Data Report

Overview

This document provides an analysis of big data technologies and implementations, covering key aspects such as Hive Data Warehouse design, MapReduce programming, and Big Data Project Analysis. The report includes SQL queries executed in Apache Hive, MapReduce implementations, and discussions on cloud-based big data processing.

Contents

Hive Data Warehouse Design

Creation of tables (Products, Customers, Sales) using Hive.

Data loading procedures using .csv files.

Execution of SQL queries to analyze sales, customer behavior, and product statistics.

MapReduce Programming

Implementation of a MapReduce program to calculate the average number of authors per paper for each year.

Explanation of the in-mapper combiner approach to reduce network traffic and improve performance.

Analysis of the advantages and limitations of the implemented approach.

Big Data Project Analysis

Comparison of data lakes vs. data warehouses for financial data management.

Discussion on the limitations of Hadoop MapReduce for real-time processing and recommendations for alternative stream processing frameworks.

Cloud-based big data processing strategies, including security measures, scalability, and global data center advantages.

Technologies Used

Apache Hive: For data warehouse design and SQL queries.

MapReduce: For large-scale data processing.

Apache Spark & Hadoop: Discussed as big data processing frameworks.

Cloud Platforms: AWS, Google Cloud, Microsoft Azure.

Key Findings

Hive provides efficient querying capabilities for structured datasets.

MapReduce can be optimized using in-mapper combiners but has scalability and memory limitations.

Data Lakes are preferable over traditional Data Warehouses for large, diverse datasets.

Stream Processing (e.g., Apache Flink, Apache Kafka Streams) is better suited for real-time analytics.

Cloud Computing enables scalability, redundancy, and security enhancements for big data processing.

References

Microsoft Azure: What is a Data Lake?

Saeed Shahrivari: "Beyond Batch Processing: Towards Real-Time and Streaming Big Data" (2014)

Ajay Yadav: "The Role Played by Cloud Computing in Big Data" (2022)

Usage Instructions

If using Apache Hive, ensure the required tables are created and .csv files are available.

Run the SQL queries sequentially for data analysis.

If testing MapReduce, set up a Hadoop environment and execute the provided Java code.

Use cloud-based processing tools for scalability and efficiency in big data analysis.

Author

Fatmanur Ertaş

Contact

Email: fatma.ertas@outlook.comLinkedIn: Fatmanur Ertaş

