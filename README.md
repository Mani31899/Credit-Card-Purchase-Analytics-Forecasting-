# Credit-Card-Purchase-Analytics-Forecasting

## Project Overview
**1. Data Transformation and Machine Learning Model Development**
   - Designed analytical transformations for customer credit data in Azure Databricks.
   - Developed an 90% accurate Classification Machine Learning model for credit card purchase prediction.

**2. Integration with Visualization Tools**
   - Integrated the analysis and the model with Power BI to display the analysis as a dashboard.
   - Utilized over 10 features for comprehensive visualization and analysis.

## Key Components
- **Azure Data Lake Gen2**: Utilized to store the CSV file and mounting it to the Azure Databricks for an efficient Data Ingestion and Analysis.
- **Azure Databricks**: For layered data processing/cleaning and implementing Spark functions for analysing each of the customer features.
- **Power BI**: Integrated for dynamic reporting and visualization of both the insights and the forecasted result.
- **Security**: Reinforced through the implementation of Azure Active Directory and Key Vault for mounting Datalake on Databricks.

## Project Workflow
1. **Data Ingestion**: Data from the Data Lake Gen 2 is ingested into Azure Databricks through mounting with appropriate Key Valut secrets.
2. **Data Processing**: The ingested data underwent transformation through Databricks, ensuring it was formatted and optimized for analysis.
3. **Data Analysis for Business Insights**: The transformed data is then further analysed using user defines pyspark functions for each of the customer features and plots are shown.
4. **Machine Learning Implementation**: The data is then split to train and text the data on a Logistic Regression model to predict whether a customer would buy a credit card or not.
5. **Dasboards and Reporting**: This data wis then connected to Power BI for the creation of insightful visualizations and reports along with the forecasted result of the credit card buyers.
