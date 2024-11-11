1. Uploading Data to Power BI
Open Power BI Desktop.
Go to Home > Get Data. Choose the data source type (e.g., Excel, SQL Server, Web).
Select and connect to the data source.
Preview the data, then click Load to import it into Power BI.
2. Updating Data
When working with data that’s subject to changes, Power BI can refresh it.
Go to Home > Refresh to update the data manually.
For automatic refresh (especially for cloud-based data sources), publish the report to the Power BI Service and set up a scheduled refresh in the Settings of your Power BI workspace.
3. Data Cleaning
Power BI’s Power Query Editor is used for data cleaning.
Open Power Query by selecting Transform Data on the Home tab.
Common data-cleaning tasks include:
Removing duplicates: Right-click the column > Remove Duplicates.
Handling missing values: Replace blanks or nulls with specific values by selecting Transform > Replace Values.
Splitting and merging columns: Use the Split Column or Merge Columns features for adjustments.
Formatting data types: Ensure columns are set to the correct data types (e.g., Text, Date, Number) for accurate analysis.
4. Data Mining in Power BI
Data mining in Power BI involves using visuals and DAX (Data Analysis Expressions) for deeper insights.
Apply data mining techniques by:
Creating calculated columns and measures with DAX for custom analysis (e.g., sales growth, running totals).
Using filters and slicers to drill down into specific data.
Using AI visuals: Like Q&A (for natural language queries), Decomposition Tree (for analyzing multiple factors), and Key Influencers (for identifying important factors in your data).
5. Data Transformation and Modeling
Once the data is clean, you can create relationships between tables to build a data model.
Go to Model view to establish relationships, which are crucial for combining data from multiple tables.
