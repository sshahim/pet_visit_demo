# pet_visit_demo
## notebooks and how to deploy and run
These are scripts that are used in the main notebook (pet_visit_modelling.dbc)
- read_source_mapping.dbc
- ingestion.dbc
- cleansing.dbc
- validation.dbc
- modelling.dbc

In order to run the pipeline we need to upload 2 files to Azure Databricks DBFS and run pet_visit_modelling.dbc notebook. 

- source_mapping-6.json => "dbfs:/FileStore/tables/source_mapping-6.json"
- modelling_1.xlsx => "dbfs:/FileStore/tables/modelling_1.xlsx"

