# AzureDatabricksDataEngineering
Repo to hold notebooks and data for Azure Databricks Data Engineering Training

- Import the DBC files in Azure Databricks workspace
- Upload the parquet and CSV file via Browse DBFS

# Modules Covered
- Delta Lake basics
- How to set up Medallion Architecture
- How to set up Medallion Architecture using Delta Live Tables


# Exceution Steps 

##### The modules can be executed in any order but a recommended approach is as below 

## Delta Lake Basics

- Import the DeltaLake.dbc file under your user in Azure databricks workspace
- Below notebooks should be imported under the DeltaLake folder

  <img width="396" alt="image" src="https://github.com/mahes-a/AzureDatabricksDataEngineering/assets/120069348/4c3f4e1d-7ca2-4870-a56f-53f23b9809b3">

- Execute the DeltaLake-Create Data notebook followed by 01-Getting-Started-With-Delta-Lake and 02-Delta-Lake-Performance

## Medallion Architecture

- Import the green_tripdata_2023-09.parquet and taxizonelookup.csv into DBFS

  <img width="383" alt="image" src="https://github.com/mahes-a/AzureDatabricksDataEngineering/assets/120069348/300e65ee-1452-4434-b6a7-e909300a0ae1">

- Import the MedallionDelta.dbc and execute the SimpleMedallion notebook

  <img width="204" alt="image" src="https://github.com/mahes-a/AzureDatabricksDataEngineering/assets/120069348/1e1ad874-96f4-4724-84f7-2641270e69a7">


## Delta Live Table with Medallion Architecture

- Import the DeltaLiveTable.dbc into user folder
  
- Setup the DeltaLive table using below notebook

  <img width="397" alt="image" src="https://github.com/mahes-a/AzureDatabricksDataEngineering/assets/120069348/c7a27d7a-3dbf-4425-80bc-e4404b997b36">


