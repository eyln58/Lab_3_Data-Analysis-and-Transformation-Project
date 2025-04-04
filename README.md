# Azure Synapse Analytics Data Analysis and Transformation Project

This project leverages Azure Synapse Analytics and Azure Data Lake Storage to perform data analysis and transformation. It involves loading sales data in CSV files into a data lake, querying, transforming, and persisting the results.

## Project Scope

The project encompasses the following tasks:

### 1. Data Preparation and Exploration
- **Created** an Azure Synapse Analytics workspace and an Azure Storage account.
- **Uploaded** sales data CSV files to the data lake.
- **Used** Synapse Studio to view and inspect the files (e.g., CSV files in the `sales` folder) in the data lake.

### 2. Querying Data with SQL
- **Utilized** Serverless SQL Pool to query the CSV files.
- **Employed** the `OPENROWSET` function to retrieve data and ran simple queries, such as selecting the top 100 rows.
- **Adjusted** queries to recognize header rows in the files.

### 3. Data Transformation and External Table Creation
- **Defined** a data lake location using `CREATE EXTERNAL DATA SOURCE`.
- **Used** `CREATE EXTERNAL TABLE AS SELECT` (CETAS) to transform sales data (e.g., calculating total sales and net revenue per product).
- **Saved** transformation results to the data lake in Parquet format and made them queryable as an external table.

### 4. Automation with Stored Procedures
- **Developed** a stored procedure to aggregate sales data by year.
- **Designed** the procedure to drop old data and write new transformation results to the data lake.
- **Executed** the procedure, resulting in a new folder and Parquet files in the data lake.

### 5. Validation of Results
- **Verified** the created external tables and data lake files in Synapse Studio.
- **Confirmed** transformation results by running SQL queries.

## What I Learned

Through this project, I gained the following insights and skills:
- **Azure Synapse Analytics**: Learned to query external data with Serverless SQL Pool and transform it using CETAS.
- **Data Lake Integration**: Understood how Synapse integrates with Azure Data Lake Storage.
- **External Tables vs. Data Sources**: Grasped the benefits of defining external data sources and making data queryable as tables.
- **SQL for Big Data**: Acquired the ability to analyze and transform large datasets using SQL.
- **Automation**: Gained experience in automating data processes with stored procedures.
- **Problem-Solving**: Addressed practical challenges, such as managing existing files in the data lake (e.g., deleting old data before re-running transformations).

This project provided a **solid foundation** in big data analytics and cloud-based data processing.

## Contact

Feel free to reach out to me on LinkedIn for more details:  
[**LinkedIn Profile**](https://www.linkedin.com/in/eyilan/)
