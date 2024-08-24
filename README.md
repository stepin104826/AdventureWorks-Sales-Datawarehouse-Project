# AdventureWorks ETL Data Warehousing Solution

## Project Overview

The goal of this project was to create a comprehensive data warehousing solution for AdventureWorks Database, focusing on the company's bike sales data. By extracting, transforming, and loading the data into a centralized SQL Server Management Studio (SSMS) data warehouse, we enable in-depth analysis and visualization of sales trends and performance metrics using SSAS and Power BI.

## Technologies Used

- **SQL Server Management Studio (SSMS)**: To manage and query the SQL Server database where the transformed data is stored.
- **SQL Server Integration Services (SSIS)**: For extracting, transforming, and loading (ETL) data from various source database using ETL packages and data flows into an SSMS data warehouse.
- **SQL Server Analysis Services (SSAS)**: For building OLAP tabular models to analyze and aggregate data.
- **Power BI**: For creating interactive dashboards and visualizations based on the data processed through SSAS models.

## Setup and Installation

1. **Install SQL Server and SSMS**: Ensure you have SQL Server and SQL Server Management Studio installed on your machine.
2. **Install SSIS and SSAS**: Add SQL Server Integration Services and SQL Server Analysis Services to your SQL Server installation.
3. **Power BI Desktop**: Download and install Power BI Desktop from the official Microsoft website.
4. **Clone the Repository**: Clone this GitHub repository to your local machine using:
    ```bash
    git clone https://github.com/stepin104826/AdventureWorks-Sales-Datawarehouse-Project
    ```

## ETL Process

1. **Data Extraction**: SSIS packages are used to extract bike sales data from various source systems (e.g., CSV files, existing databases).
2. **Data Transformation**: The extracted data is cleaned, transformed, and standardized to fit the schema of the target SSMS data warehouse. Transformation tasks include data cleansing, type conversion, and aggregation.
3. **Data Loading**: Transformed data is loaded into the SSMS data warehouse, ready for analysis. The data is stored in structured tables optimized for query performance and analysis.

## Data Analysis and Visualization

1. **OLAP Tabular Models**: SSAS is used to create OLAP tabular models, allowing for multidimensional analysis of the bike sales data. These models support complex queries and provide fast response times for data aggregation.
2. **Power BI Dashboards**: DAX queries are utilized to create interactive and insightful Power BI dashboards. These dashboards offer visual insights into sales performance, trends, and other key metrics.

## Results

- Successful creation of a scalable ETL process for managing AdventureWorks bike sales data.
- Enhanced data analysis capabilities through SSAS tabular models.
- Interactive Power BI dashboards providing actionable insights into sales trends and performance.

## Future Work

- Integration of additional data sources to expand the dataset.
- Implementation of predictive analytics to forecast sales trends.
- Optimization of ETL processes for improved performance.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or report any issues. Before contributing, ensure that your changes align with the project goals and standards.
