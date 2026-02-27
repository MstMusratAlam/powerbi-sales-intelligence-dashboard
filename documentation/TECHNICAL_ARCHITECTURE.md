# Technical Architecture Documentation

## System Design

The Power BI Sales Intelligence Dashboard is designed to provide a comprehensive overview of sales data across various dimensions. The architecture of the system is primarily centered around data ingestion, transformation, and visualization.

1. **Data Sources**: The system pulls data from various sources such as:
    - SQL Server databases
    - Excel files
    - Cloud storage services (e.g., Azure Blob Storage)

2. **Data Ingestion**: Using ETL (Extract, Transform, Load) processes, data is collected and prepared for analysis.

3. **Data Transformation**: The data is cleansed and structured for compatibility with Power BI. Key transformations include:
    - Merging datasets
    - Calculating metrics and KPIs
    - Filtering and aggregating data

4. **Data Storage**: The transformed data is stored in an optimized format for reporting, typically in a star or snowflake schema.

5. **Visualization**: Power BI dashboards visualize the data, enabling users to:
    - Analyze sales performance
    - Track trends over time
    - Interpret data across different regions and products

## Data Model Details

The data model consists of:

- **Fact Tables**: These tables store quantitative data for analysis, such as sales amount, quantity sold, etc.

- **Dimension Tables**: These tables provide context to the facts, including:
    - **Time Dimension**: Stores date-related information for time-based analysis.
    - **Product Dimension**: Contains details about products sold (e.g., product IDs, names, categories).
    - **Customer Dimension**: Includes information about customers (e.g., customer IDs, names, demographics).

### Relationships

- The fact table is connected to each dimension table through foreign keys, allowing for rich analytical queries.
- Relationships are set to enable slicing and dicing of data across various dimensions which enhances reporting capabilities.

### Summary

This architecture leverages the capabilities of Power BI to present sales data in an intuitive manner, making it easier for stakeholders to make informed decisions.
