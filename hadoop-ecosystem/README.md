 HADOOP Project

## Project Overview

This project uses the Hadoop ecosystem to process and analyze the MovieLens 10k dataset. Data is ingested into HDFS and processed with MapReduce, Hive, Spark, Pig, and Sqoop. It demonstrates how different Hadoop components handle storage, querying, and large-scale processing, providing a comparative view of their efficiency and usability.
### Project Architecture
The MovieLens 10k Project showcases how different Hadoop ecosystem components handle big data, from ingestion in HDFS to processing with MapReduce, Hive, Spark, and Pig, and finally data export, highlighting each tool’s strengths in the pipeline.

### Architecture Overview

The project architecture involves the following key steps:

1. **Data Ingestion**: The  dataset is ingested into Hadoop Distributed File System (HDFS), providing a reliable and scalable storage solution.
2. **Data Processing**: Various processing frameworks are utilized to transform and analyze the data:
   - **MapReduce**: The traditional Hadoop processing framework, showcasing basic distributed data processing.
   - **Hive**: A data warehousing solution that allows for querying data using SQL-like syntax.
   - **Pig**: A high-level scripting language for expressing data transformations.
   - **Spark**: A fast and general-purpose cluster computing system for large-scale data processing.
   - **Tez**: An application framework that enables a complex directed-acyclic-graph of tasks for processing data, improving performance over traditional MapReduce.
3. **Data Import/Export**: Sqoop is used for transferring data between HDFS and relational databases, enabling seamless integration between Hadoop and traditional RDBMS.

