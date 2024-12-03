
![Pasted image 20241203145633](https://github.com/user-attachments/assets/dfa1c1cf-f64f-4275-9bb0-0f56c625d4db)


# Airline Data Processing Pipeline with Azure Synapse

## **Project Description**

This project demonstrates the use of **Azure Synapse Analytics**, **Azure Synapse Spark Pool**, **Azure Storage**, and **Power BI** to build a data pipeline for processing and analyzing an Airline dataset. The pipeline transforms data, stores it in Spark pool tables, and visualizes insights in Power BI, leveraging **Apache Spark** for efficient big data analytics.

---

## **Business Overview**

Azure Synapse Analytics integrates **big data processing** and **enterprise data warehousing** into a unified platform. This project utilizes serverless **Apache Spark pools** in Azure Synapse for real-time data transformation, with compatibility for **Azure Storage** and **Azure Data Lake Gen2 Storage**. The streamlined architecture ensures efficient processing, storage, and visualization of airline operational data.

---

## **Data Description**

The Airline dataset contains ~4000 records with fields such as:
- **Date**  
- **Flight carrier details**  
- **Origin and destination details**  
- **Delay reasons**  
- **Distance**  
- **Elapsed time**  

---

## **Tech Stack**

- **Framework:** Apache Spark  
- **Languages:** SQL, Python  
- **Services:** Azure Synapse Analytics, Azure Synapse Spark Pool, Azure Storage, Power BI  

---

## **Key Components**

1. **Azure Synapse Analytics:**  
   - Unified analytics service for querying, managing, and delivering data.  
   - Supports serverless and provisioned **Apache Spark pools**.

2. **Azure Storage:**  
   - Highly available and scalable storage for data ingestion and transformation.

3. **Azure Synapse Spark Pool:**  
   - Processes large-scale data with **in-memory computing** for speed and efficiency.  
   - Handles data transformations and table creation.

4. **Power BI:**  
   - Visualizes transformed data, providing actionable insights.

---

## **Approach**

1. **Data Ingestion:**  
   - Read airline data from Azure Storage using Synapse Spark pools.  

2. **Data Transformation:**  
   - Load data into Spark DataFrames.  
   - Create temporary views for exploratory analysis.  
   - Save results as permanent tables in the Spark pool.  

3. **Visualization:**  
   - Use Power BI to connect to processed tables and generate visualizations for delay analysis, flight carrier performance, and route metrics.

---

## **Key Insights**

- Analyze flight delays and their causes.  
- Evaluate airline and route performance.  
- Gain insights into distance and time efficiency for operations.

---

## **How to Run the Project**

1. **Set Up Azure Services:**  
   - Create Azure Synapse workspace, Spark pools, and Azure Storage.  

2. **Process Data:**  
   - Use Synapse Studio to configure Spark pools and process data using notebooks.  

3. **Store and Visualize:**  
   - Save transformed data in Spark tables.  
   - Use Power BI for visualization and reporting.  

---

## **Contact**

For questions or feedback, feel free to reach out!
