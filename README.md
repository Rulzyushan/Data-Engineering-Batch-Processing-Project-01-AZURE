# Data-Engineering-Batch-Processing-Project-01
### **Project Overview**
This project focuses on building a scalable and automated data pipeline to ingest, process, and analyze GitHub data using Azure services. 

- **Data Ingestion:** Extracting GitHub data files and storing them in Azure Data Lake.  
- **Automated Data Pipeline:** Using Azure Data Factory to orchestrate and automate data transfer from GitHub to Azure Data Lake.  
- **Data Transformation:** Leveraging Azure Databricks to clean, process, and transform raw GitHub data into an analytical dataset.  
- **Data Storage & Querying:** Loading the transformed data into Azure Synapse Analytics SQL Database for efficient querying.  
- **Visualization & Insights:** Creating Power BI dashboards to analyze key metrics and trends.  

### **Architecture Diagram**
![Architecture-Diagram](Architecture-Diagram.png?raw=true)

### **Azure Cloud Setup**
- Create a resource group named **DE-BP-Project-01** to manage all related Azure services. 
- Deploy Azure Data Factory, Azure Data Lake Storage, Azure Databricks, Azure Synapse Analytics, and Azure Key Vault.
- Store GitHub Access Token in Azure Key Vault.
- In Azure Data Lake resource and create three containers under Data Storage:  
   1. **Bronze**: Store raw, ingested data for initial processing.
   2. **Silver**: Store enriched data that has been cleansed and transformed.
   3. **Gold**: Store the final, transformed data ready for analytics and reporting.

### **Azure Data Factory**
- Create a Linked Service for HTTP in ADF.
- In the HTTP linked service configuration, Used the GitHub base URL for repository files and the Personal Access Token.
- Create a Dataset for GitHub Files and Choose HTTP as the dataset type. Set the Linked Service to the HTTP linked service.
- Choose the File format CSV.
### **Azure Cloud Setup**
### **Azure Cloud Setup**
### **Azure Cloud Setup**
