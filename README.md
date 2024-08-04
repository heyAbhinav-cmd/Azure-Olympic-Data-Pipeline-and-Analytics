**Olympic Data Analytics Project**

 Overview
This project demonstrates an end-to-end data engineering solution using Azure Cloud services. We will extract Olympic data from an API using Azure Data Factory, transform it with Azure Databricks, and analyze it using Azure Synapse Analytics. Finally, we'll visualize the results using tools like Power BI.

 Project Architecture
1. Data Source: Olympic data available on Kaggle.
2. Azure Data Factory: Extract data from the source and load it onto Azure Data Lake Storage.
3. Azure Databricks: Write Spark code to transform the data.
4. Azure Synapse Analytics: Run SQL queries on the transformed data to derive insights.
5. Visualization: Create dashboards using Power BI.

Prerequisites
- A stable internet connection.
- Basic knowledge of Python and SQL.
- An Azure account (12-month free trial with $200 credit).

Data Source
The dataset contains information about:
- Athletes
- Coaches
- Entries by gender
- Medals
- Teams

find the dataset on Kaggle or use the data uploaded to this repository.

 Steps to Execute the Project

1. Setting Up Azure Data Factory
- Use Azure Data Factory to build a data pipeline.
- Extract data from Kaggle and load it onto Azure Data Lake Storage.

2. Data Transformation with Azure Databricks
- Write Spark code in Azure Databricks.
- Perform data transformations (cleaning, removing duplicates, applying business logic).
- Load transformed data back to Azure Data Lake Storage.

3. Analyzing Data with Azure Synapse Analytics
- Use Azure Synapse Analytics to run SQL queries.
- Derive insights, such as the country with the most gold medals or the top-performing athletes.

4. Visualization
- Create dashboards using Power BI or other visualization tools.
- Visualize insights derived from the transformed data.

Detailed Instructions
Azure Account Setup
1. **Create an Azure Account**: [Azure Free Trial](https://azure.microsoft.com/en-us/free/)
2. **Set Up Resources**:
    - Create a Resource Group.
    - Create a Data Lake Storage account.
    - Set up Azure Data Factory.
    - Configure Azure Databricks.
    - Set up Azure Synapse Analytics.

Data Pipeline
1. Data Extraction:
    - Configure Azure Data Factory to connect to Kaggle.
    - Extract raw data and load it into Azure Data Lake Storage.

2. Data Transformation:
    - Use Azure Databricks to write Spark code for data transformation.
    - Save the transformed data back to Azure Data Lake Storage.

3. Data Analysis:
    - Use Azure Synapse Analytics to run SQL queries on the transformed data.
    - Analyze the data to derive insights.

4. Data Visualization:
    - Connect Power BI to Azure Synapse Analytics.
    - Create dashboards to visualize the data.

Resources
- [Azure Data Factory Documentation](https://docs.microsoft.com/en-us/azure/data-factory/)
- [Azure Databricks Documentation](https://docs.microsoft.com/en-us/azure/databricks/)
- [Azure Synapse Analytics Documentation](https://docs.microsoft.com/en-us/azure/synapse-analytics/)
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)

 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Acknowledgments
- Special thanks to the creators of the Kaggle dataset.
- Thanks to Microsoft for providing comprehensive documentation on Azure services.

 Author
Abhinav Kadam  
Email: [abhinavkadam2001@gmail.com](mailto:abhinavkadam2001@gmail.com)

