# Airlines-Project---Azure-End-to-End-Data-Engineering-Pipeline
Project showcasing azure data engineering skills as applicable to aviation datasets by leveraging Azure paltform and using data engineering resiurces like Databricks, ADF and others.

# Process and requirements
a. Load data from different source with differenrt type of data.
   1. Blob - excel , pdf.
   2. Azure SQL database - 2 tables.
   3. Azure datalake gen 2 - 1 zip folder, 1 csv file.
   4. API
b. Dump above mention data into Gen 2 raw container day wise.
c. Clean the data and create cleansed delta tables.
d. Create Fact and Dimension based on business logic and save the data into ADLS Gen2 (Mart container/ layer)
e. Publish tha data into Publish Gen2 layer and Azure SQL DB/ DW
f. Create PowerBI report and vizualize the charts needed.
g. Send publish data to respective owners based on given excel file.
h. Create CI/CD pipeline to deploy the code to PROD environment.
   
# Important guidelines to be followed.
1. Validate the data between source and sink.
2. Send alerts when data is raw or junk (Data quality checks).
3. Send alerts when pipelines get failed.
4. Use minimum resources as much as possible , use frameworks which can be used in other projects too.

# List of tools to be used.
1. Azure Data Factory
2. Azure Databricks
3. Logic app
4. Pyspark, SQL, python , Spark SQL
5. Automation RunBook
6. Azure SQL Database/Synapse Analytics
7. Azure Blob Storage
8. Azure Datalake gen2
9. PowerBI
10. Azure Devops

